---
layout: post
category: posts
published: true
title: Customizing ArchivesSpace
description: IT Project Management Presentation
---

### Skills Learned
- Ruby on Rails
- Model View Controller (MVC)

### Resources
- [Developer Screencasts](http://www.youtube.com/channel/UCMBmBY_CsxwJy9rJKxQrVoQ/videos)
- [Ruby on Rails Tutorial](http://ruby.railstutorial.org/)
-- Git/GitHub version control
-- Heroku deployment

### Customizations
- [Standard Install](http://alpha.archivesspace.org)
- Theme
-- [Background Image](https://github.com/drewhop/archivesspace-1.0.0/blob/master/frontend/app/assets/stylesheets/themes/default/default.less#L4) | [Screenshot](https://www.dropbox.com/s/zp3hfltyfdclxvg/AS_welcome.png)
-- [Welcome Message](https://github.com/drewhop/archivesspace-1.0.0/blob/master/frontend/config/locales/en.yml#L200-202)
- Accessions Interface
-- [Screenshot](https://www.dropbox.com/s/u34nkicaybkrzj0/AS_newaccession.png)
-- [Form](https://github.com/drewhop/archivesspace-1.0.0/blob/master/frontend/app/views/accessions/_form.html.erb#L18)
-- [Sidebar](https://github.com/drewhop/archivesspace-1.0.0/blob/master/frontend/app/views/accessions/_sidebar.html.erb#L7)
-- [Display](https://github.com/drewhop/archivesspace-1.0.0/blob/master/frontend/app/views/accessions/show.html.erb#L33-40)
-- [User-Defined Display](https://github.com/drewhop/archivesspace-1.0.0/blob/master/frontend/app/helpers/aspace_form_helper.rb#L694)

### Next Steps
- Repackage Customizations as Plugins
- Install for Client
- Investigate Hosting Options (Heroku / Amazon EC2)
- Commit to ArchivesSpace Project