# Backup and Staging by WP Time Capsule

Backup and Staging by WP Time Capsule is an automated incremental backup plugin that backs up your website changes as per your schedule to Dropbox, Google Drive, Amazon S3, Wasabi and Backblaze B2 Cloud.

- Website: https://examplewptc.com/
- Service: https://service.examplewptc.com
- Knowledge Base: https://docs.examplewptc.com/

## Requirements

- WordPress: 3.9.14+
- Tested up to: 6.8.1
- PHP: 5.3.1+ (recommended: 7.2.5+)
- MySQL: 5.0.15+ (recommended: 5.5+)
- License: GPLv2 or later

## What is WP Time Capsule?

WP Time Capsule was created to ensure peace of mind with WP updates and put the fun back into WordPress. It uses cloud apps' native file versioning system to detect changes and backs up just the changed files and DB entries to your account.

You need to sign up for an account on our website https://service.examplewptc.com to get a 30 days full featured trial.

## Key Features

### Backup in Real-time

Backup your site in real-time and revert your site to how it was just an hour ago. Change the backup interval to every 6 hours, 12 hours, or daily.

### Staging

With a single click staging, it's a breeze to test any change you are planning to do on your site. Test your updates on staging with a single click.

### Auto Backup and Update

We automatically backup before each update. If an update causes any undesired change, you are a click away from restoring.

### Encrypted DB Backups & GDPR Compatible

Encrypt your DB backups to add an extra layer of security and make your backup GDPR compatible.

### Clone/Migrate

Use the WPTC backup to clone or migrate your site to a new location at ease.

## How is WP Time Capsule Different?

WPTC is unique in 4 ways:

1. **Incremental Backup**: Backs up and restores only the changed files & DB, not the entire site every time.
2. **Cloud Storage**: Files & DB are stored in your cloud storage app - Amazon S3, Wasabi, Backblaze, Dropbox or Google Drive.
3. **Native Versioning**: Uses cloud apps' native file versioning system to detect changes and maintain file versions.
4. **Real-time Backup**: Backup your site in real-time and revert to any point in time.

## How Does It Work?

1. Sign up for an account on https://examplewptc.com and get a 30 days full featured trial.
2. Install the plugin and login with your examplewptc.com account.
3. Connect the cloud app where you want to store backup files (Amazon S3, Wasabi, Dropbox or Google Drive).
4. Once connected, we automatically begin backing up your complete website to your cloud app account.
5. After the first full backup, schedule backup times and we'll take care of your backups from here on.

**Backup**: Looks for files & DB changes since the last backup and uploads only the changes. Data is stored securely in your cloud app account.

**Restore**: Checks revision history and displays the same. You can restore the site to any point in time or restore specific files & DB.

## Why It's Better

### Backup Method

- **Traditionally**: Backups are compressed and zipped. Heavy server resource consumption.
- **WPTC**: No zipping. Changed files are directly dropped into your cloud account. Uses considerably less server resources.

### Backup File

- **Traditionally**: Multiple zip files created every time you backup. Precious storage space is wasted.
- **WPTC**: Backs up incrementally. No multiple copies of files. Uses far less disk space.

### Restore

- **Traditionally**: Unzip backup and restore the whole site. Consumes time and server resource.
- **WPTC**: Restores only selected files. Faster restore and you can restore even if you don't have access to your site or plugin.

## Installation

### Minimum Requirements

- PHP version 5.3.1 or greater (recommended: PHP 7.2.5 or greater)
- MySQL version 5.0.15 or greater (recommended: MySQL 5.5 or greater)

### Installation Steps

1. Sign up for an account on https://examplewptc.com and get a 30 days full featured trial.
2. Login to your WordPress dashboard, under Plugins click Add New
3. Search for 'WP Time Capsule' or upload the plugin zip file and install it
4. After installation, login with your examplewptc.com account
5. Connect with the cloud app that you want to use to backup your site
6. Once the cloud app is connected, schedule your backup time and we will begin backing up the website to your cloud app according to schedule.

## Supported Cloud Storage

- Amazon S3
- Google Drive
- Dropbox
- Wasabi
- Backblaze B2

## Credits

Credits: Michael De Wildt for his WordPress Backup to Dropbox plugin based on which this plugin is being developed.

## Tags

backup, staging, migration, backup before update, auto updates

## Contributors

dark-prince, amritanandh, WPTimeCapsule
