# Sample Content
A custom import sample content module.

#### Dependency
- https://www.drupal.org/project/default_content

#### Document
- https://www.drupal.org/docs/contributed-modules/default-content-for-d8

#### Drush command examples
```
drush sqlq 'SELECT uuid FROM block_content'
drush sqlq 'SELECT uuid FROM comment'
drush sqlq 'SELECT uuid FROM file_managed'
drush sqlq 'SELECT uuid FROM media'
drush sqlq 'SELECT uuid FROM menu_link_content'
drush sqlq 'SELECT uuid FROM node'
drush sqlq 'SELECT uuid FROM taxonomy_term_data'
```

#### Export sample content
```
drush default-content:export-module PREFIX_sample_content
```
