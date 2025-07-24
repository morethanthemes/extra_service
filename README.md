# Extra Service

## Description

This module provides a "Service" content type for Drupal websites, along with associated fields, vocabularies, and display configurations.

## Prequisites

This module assumes that the following modules are installed and enabled on your Drupal site:
- [Paragraphs](https://www.drupal.org/project/paragraphs)
- [Image Widget Crop](https://www.drupal.org/project/image_widget_crop)
- [Video Embed Field](https://www.drupal.org/project/video_embed_field)
- Extra View Modes
- Extra Paragraphs


## Requirements

This module requires the following Drupal core modules:
- Entity Reference Revisions
- File
- Image
- Link
- Menu UI
- Node
- Path
- Taxonomy
- Text
- User

## Installation

1. Install the module as you would normally install a contributed Drupal module. See the [Drupal documentation](https://www.drupal.org/docs/extending-drupal/installing-modules) for further information.
2. Enable the module in the "Extend" section of your Drupal site.

## Configuration

This module provides the following configuration:
- A "Service" content type with the machine name `mt_service`.
- Several fields for the "Service" content type, including banner images, body content, highlights, images, links, tags, and videos.
- A "Service Tags" taxonomy vocabulary with the machine name `mt_service_tags`.
- Several entity view displays for the "Service" content type, including default, featured teaser, metro tile, slide view, teaser tile, and video grid item displays.
- Several entity form displays for the "Service" content type.

All configuration is exported in the `config/install` directory and will be imported when the module is enabled.
