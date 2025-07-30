# Extra Service

## Description

This recipe provides a "Service" content type for Drupal websites, along with associated fields, vocabularies, and display configurations.

## Prequisites

This recipe assumes that the following modules are installed and enabled on your Drupal site:

- [Paragraphs](https://www.drupal.org/project/paragraphs)
- [Image Widget Crop](https://www.drupal.org/project/image_widget_crop)
- [Video Embed Field](https://www.drupal.org/project/video_embed_field)

This recipe assumes that the following recipes are installed on your Drupal site:

- Extra View Modes
- Extra Paragraphs

## Requirements

This recipe requires the following Drupal core modules:

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

```bash
# From your Drupal root directory
drush recipe ../recipes/extra_service
```

## Configuration

This recipe provides the following configuration:

- A "Service" content type with the machine name `mt_service`.
- Several fields for the "Service" content type, including banner images, body content, highlights, images, links, tags, and videos.
- A "Service Tags" taxonomy vocabulary with the machine name `mt_service_tags`.
- Several entity view displays for the "Service" content type, including default, featured teaser, metro tile, slide view, teaser tile, and video grid item displays.
- Several entity form displays for the "Service" content type.

All configuration is exported in the `config/install` directory and will be imported when the recipe is installed.
