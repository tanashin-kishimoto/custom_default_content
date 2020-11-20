# Custom Default Content
Custom default content module template.

#### Dependency
- https://www.drupal.org/project/default_content
- Version ^2.0

#### Document
- https://www.drupal.org/docs/contributed-modules/default-content-for-d8

#### Drush search uuid command examples
```
drush sqlq 'SQL STATEMENT'
drush sqlq 'SELECT uuid FROM node WHERE nid = 1'
```
```
drush sqlq 'SELECT uuid FROM block_content'
drush sqlq 'SELECT uuid FROM comment'
drush sqlq 'SELECT uuid FROM file_managed'
drush sqlq 'SELECT uuid FROM media'
drush sqlq 'SELECT uuid FROM menu_link_content'
drush sqlq 'SELECT uuid FROM node'
drush sqlq 'SELECT uuid FROM taxonomy_term_data'
```
#### Export content command examples
```
drush dcem custom_default_content
drush dcer node NID --folder=DIRECTORY
drush dce node NID --file=FILENAME.yml
```
