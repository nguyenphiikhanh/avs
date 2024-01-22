## Overview

This is the source of AVSCMS 8.2

AVSCMS's Official [website](https://www.avscms.com).

Detailed changes are in the [changelog](https://github.com/avscms/avscms/commits/main).

## What is AVSCMS?

AVSCMS! is a Content Management System (CMS) which enables you to build websites and powerful video sharing applications.
It is a simple and powerful web server application which requires a server with PHP and either MySQL to run. 

You can find full technical requirements [here](https://www.avscms.com/product/features/).

AVSCMS! is now free and Open Source software distributed under the GNU General Public License v3.0 or later.

> seems like they removed the documentation?
> 
> AdultVideoScript (AVS) 8.0 Documentation I. Server Requirements Please make sure that your server meets the following configuration. If you are unsure, contact your hosting company / server administrator for confirmation.
> 
> Linux Server
> 
> Apache Web Server
> 
> Support for AcceptPathInfo Support for MultiViews (or mod_rewrite which is slower)
> 
> MySQL / MySQLi
> 
> PHP 5.x / 7.x (mod_php/CGI)
> 
> Support for GD2 Library Support for MySQL / MySQLi Support for Curl Recommended PHP Configuration safe_mode off open_basedir off max_execution_time 7200 max_input_time 7200 memory_limit (with 1MB more then the maximum video upload size) post_max_size (maximum video upload size) upload_max_size (maximum video upload size) exec() should be allowed
> 
> PHP CLI 5.x (see above + register_argc_argv ON)
> 
> FFmpeg (Recommended Version: 3+)
> 
> II. Installation and Configuration Instructions
> 
> 1. Edit include/config.paths.php and set $config['BASE_URL'] to your site's url.
> 2. OPTIONAL: If you use a subdirectory for your installion set $config['RELATIVE'] to your subdirectory (eg: $config['RELATIVE'] = '/subdirectory')!
> 3. OPTIONAL: If you use a subdirectory for your installation edit loader.php and set $relative to your subdirectory (eg: $relative = '/subdirectory')!
> 4. Create a database. Edit include/config.db.php and set the database information (name, user and password).
> 5. Import the sql dump from sql/avs.sql in your database (most likely using phpMyAdmin).
> 6. Upload all files and folders from /upload to your server.
> 7. Chmod following files and directories to 0777. You can also fix the file/directory permissions from the admin panel: Settings > General > System Check
> 
> /include/config.local.php /cache/frontend /cache/backend /images/logo /images/notice_images /images/notice_images/thumbs /media/albums /media/categories/album /media/categories/video /media/csv /media/photos /media/photos/tmb /media/player/logo /media/users /media/users/orig /media/videos/tmb /media/videos/vid /media/videos/h264 /templates/backend/default/analytics/analytics.tpl /templates/emails /templates/emails/_.tpl /templates/frontend/(your_template)/static/_.tpl /tmp/albums /tmp/avatars /tmp/downloads /tmp/logs /tmp/sessions /tmp/thumbs /tmp/uploader /aembed.sh
> 
> 8. Go to [www.domain.com/siteadmin](http://www.domain.com/siteadmin) (login using: admin/admin) and start configuring your website.
> 9. You can use the Google Video Sitemap generator using the link: http://www.yourdomain.com/sitemap.php
> 10. Enable non-www to www redirection (domain.com to [www.domain.com](http://www.domain.com)) by editing the .htaccess file and replacing "domain.com" with your domain name.


