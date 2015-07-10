# js-mobile-locales
General Information
--------------------
Main idea to share the localization files between mobile projects.

We decided to use Twin command line tool (https://github.com/mobiata/twine).


## Usage
### Tags  
  At the moment we have 3 types of tags:
  - ios
  - android
  - new

### Commands
#### For iOS
{twine} generate-all-string-files {source} {destination} --format apple --tags ios
#### For Android
{twine} generate-all-string-files {source} {destination} --format android --tags android
#### For the new strings
{twine} generate-all-string-files {source} {destination} --format {platform} --tags new
