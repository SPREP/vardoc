# 5.0.0-rc1

### Highlighted important changes since Vardoc 4.0.8:
* Issue [#3352629](http://drupal.org/i/3352629):
        Updated **Varbase profile** to `9.0.12` and **Varbase Core** to `^9.0.53`
* Issue [#3352608](http://drupal.org/i/3352608):
        Updated the patch to Allow profiles to define a **base/parent profile** to work with **Drupal 9.5.x**
# 5.0.0-beta1

* Issue [#3330522](http://drupal.org/i/3330522):
        Updated **Drupal** to `9.5.2` stable and **Varbase** to `9.0.11`
* Issue [#3307864](http://drupal.org/i/3307864)
        by [tseven](https://www.drupal.org/u/tseven),
        [narendra.rajwar27](https://www.drupal.org/u/narendrarajwar27)
        , [Rajab Natshah](https://www.drupal.org/u/rajab-natshah)
        : Fixed Unsupported operand types: `null` + `array` for **HTML input**
         styling added to custom input which is not having the `full_html` format

------------------------------------------------------------------------------------------------

# 5.0.0-alpha7

### Highlighted important changes since 5.0.0-alpha6:
* Issue [#3303762](http://drupal.org/i/3303762):
                Fixed moving the hook update for `node_type` to `entity_bundle:node`
                for Pathauto's patterns in the active configs to cover each
                 content type's module in addition to the Vardoc profile


------------------------------------------------------------------------------------------------

# 5.0.0-alpha6

### Highlighted important changes since 5.0.0-alpha5:
* Issue [#3301892](https://www.drupal.org/i/3301892):
        Changed `node_type` to `entity_bundle:node` for default pathauto
        pattern configs for all Vardoc content types
* Issue [#3301908](https://www.drupal.org/i/3301908):
        Fixed Drupal coding standards and Practices
        in `yml`, `PHP`, and `CSS` code
* Issue [#3301450](https://www.drupal.org/i/3301450)
        by [vacho](https://www.drupal.org/u/vacho)
       : Have `drupal-scaffold` locations `web-root` as docroot to fix
        composer `web-root` folder in projects
* Issue [#3302440](https://www.drupal.org/i/3302440):
        Dropped support for Composer `~1.0` in the Vardoc profile and only
        support Composer `~2.0` and later versions

------------------------------------------------------------------------------------------------

# 5.0.0-alpha5

### Highlighted important changes since 5.0.0-alpha4:

* Issue [#3290900](https://www.drupal.org/i/3290900):
        Update the Allow profiles to define a base/parent profile
        patch to work with Drupal 9.4.2
* Issue [#3270492](https://www.drupal.org/i/3270492):
        Have a default template for merge requests and issues for
        the Vardoc profile project in Gitlab
* Issue [#3256885](https://www.drupal.org/i/3256885):
        Switched Vardoc default Automated Functional Testing users creation
        to use drush user:create and drush user:role:add and use
        the default manual testing user names and emails
* Issue [#3256732](https://www.drupal.org/i/3256732):
        Added composer allow-plugins to composer.json for Vardoc
        and Vardoc Project template

------------------------------------------------------------------------------------------------

# 5.0.0-alpha4

### Highlighted important changes since 5.0.0-alpha3:
* Issue [#3217800](https://www.drupal.org/i/3217800):
        Updated the patch to Allow profiles to define a base/parent profile
        to work with Drupal 9.1.10

------------------------------------------------------------------------------------------------

# 5.0.0-alpha3

### Highlighted important changes since 5.0.0-alpha2:
* Issue [#3216603](https://www.drupal.org/i/3216603):
        Switched user page User Account Display mode ( My account ) 
       to use Varbase Layout Builder ~10
* Issue [#3216475](https://www.drupal.org/i/3216475):
        Added Organizational Units view and Organizational Units user block to
        list all organizational units for the current viewed user

### Added since 5.0.0-alpha2:
* Issue [#3215833](https://www.drupal.org/i/3215833):
        Added Group Book Integration custom code to Vardoc Groups
* Issue [#3216470](https://www.drupal.org/i/3216470):
        Added views argument plugin Group Membership Uid for a custom extra
        Contextual filters for views like Group Content: User is member
* Issue [#3215823](https://www.drupal.org/i/3215823):
        Added Entity Group Field module

### Changed since 5.0.0-alpha2:
* Issue [#3216853](https://www.drupal.org/i/3216853):
        Switched to CircleCI as the default automated testing platform
* Issue [#3216518](https://www.drupal.org/i/3216518):
        Removed Generic .main-content styling

### Updates since 5.0.0-alpha2:
* Updated [Varbase Core](https://www.drupal.org/project/varbase_core)
    module to [9.0.0](https://www.drupal.org/project/varbase_core/releases/9.0.0) stable release

### Fixes since 5.0.0-alpha2:
* Issue [#3216566](https://www.drupal.org/i/3216566)
       by [qusai taha](https://www.drupal.org/u/qusai-taha)
       : Fixed error when trying to add HTML block

------------------------------------------------------------------------------------------------

# 5.0.0-alpha2

### Highlighted important changes since 5.0.0-alpha1:
* Issue [#3215342](https://www.drupal.org/i/3215342):
        Added an Organizational Unit group type to add a group units in the organization

### Added since 5.0.0-alpha1:
* Issue [#3215329](https://www.drupal.org/i/3215329):
        Added Group invite, Group Membership Request, Group Notify, Group Taxonomy
        modules to Vardoc Content Collections
* Issue [#3215332](https://www.drupal.org/i/3215332):
        Added Announcement content type to let group members post announcements
        to visitors or unit members

### Changed since 5.0.0-alpha1:
* None

### Updates since 5.0.0-alpha1:
* None

### Fixes since 5.0.0-alpha1:
* None

------------------------------------------------------------------------------------------------

# 5.0.0-alpha1

### Highlighted important changes since Vardoc 4.0.1:
* Issue [#3118430](https://www.drupal.org/i/3118430):
        Started a 5.0.x branch for Vardoc and Vardoc Project to use Varbase 9 and Drupal 9
* Issue [#3123307](https://www.drupal.org/i/3123307):
        Drupal 9 readiness for the Vardoc distribution installation profile with Drupal coding
        standard and practice
* Issue [#3211942](https://www.drupal.org/i/3211942):
        Allowed Vardoc to work with Composer ~2.0
* Issue [#3211971](https://www.drupal.org/i/3211971):
        Switched Vardoc Homepage from Page Manager to Varbase Layout Builder ~10.0

### Added since Vardoc 4.0.1:
* Issue [#3212269](https://www.drupal.org/i/3212269):
        Added Redirect 403 to User Login module to Vardoc profile

### Changed since Vardoc 4.0.1:
* Issue [#3212481](https://www.drupal.org/i/3212481):
        Switched to Varbase Social Single Sign-On module and remove the Vardoc Google Authentication module
* Issue [#3212940](https://www.drupal.org/i/3212940):
        Switched to npm-asset/jquery-bar-rating from the custom repository antennaio/jquery-bar-rating
* Issue [#3211952](https://www.drupal.org/i/3211952):
        Remove _core and uuid from all configs
* Issue [#3178726](https://www.drupal.org/i/3178726)
        by [Joachim Namyslo](https://www.drupal.org/u/joachim-namyslo)
       : Remove patch from display suite issue 2975313 to no longer prevent updates

### Updates since Vardoc 4.0.1:
* Updated Varbase to 9.0.x
* Issue [#3178725](https://www.drupal.org/i/3178725)
        by [Joachim Namyslo](https://www.drupal.org/u/joachim-namyslo)
        : Increment font awesome to ~2.0

### Fixes since Vardoc 4.0.1:
* Issue [#3214596](https://www.drupal.org/i/3214596):
        Fixed responsive view for the LOGIN WITH and the option of OR at the user login page
* Issue [#3212070](https://www.drupal.org/i/3212070):
        Fixed Vardoc Features modules structure of configs and info
* Issue [#3213025](https://www.drupal.org/i/3213025):
        Fixed to Mark all updates by the update helper checklist as successful on install
* Issue [#3214710](https://www.drupal.org/i/3214710):
        Fixed Form Display and Full Content Display for the Article (Book page) content type
* Issue [#3212067](https://www.drupal.org/i/3212067):
        Fixed rename the Tools custom Vardoc feature module machine name to vardoc_tools ( Vardoc Tools )
* Issue [#3214212](https://www.drupal.org/i/3214212):
        Fixed JQuery SumoSelect Warning: constant(): Couldn't find constant CSS_PLUGINS
        in Library Discovery Parser
* Issue [#3214540](https://www.drupal.org/i/3214540):
        Fixed Alert message style at login and other pages