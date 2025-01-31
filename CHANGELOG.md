Changelog for SeoSuite.

SEO Suite 3.1.3
==============
- Fix alternate links (PR#95)
- Replace htmlentities htmlspecialchars for unicode characters (PR#98)
- Refactor/fix translations for Facebook/Open Graph (issue#79, PR#99)
- Move SeoSuite panel under TVs when tvs_below_content is used (issue #79)
- Change server_protocol system setting to local method (issue #90)
- Fix redirect create processor to match logic from update processor.

SEO Suite 3.1.2
==============
- Fix default permissions (PR#86)
- Fix bootstrap file to prevent FrozenServiceException (fixes #87)
- Add redirects for child resources when changing parent uri and use_alias_path is set to true

SEO Suite 3.1.1-rc8
==============
- Improved search for redirects for urls with language prefixes, like "en/", "nl/", etc.

SEO Suite 3.1.1-rc6
==============
- Fix resolvers for install on MODX3
- PHP8 compatibility fixes
- Add german translation (PR#75)
- Fix spacing in trash icon (fixes #48)
- Fix dashboard widget error (fixes #80)
- Add migration tools to CMP for migrating V1, SEO Pro and SEO Tab.
- Fix table indexes
- Add listener for 'OnBabelDuplicate'
- Fix default values for sitemap, searchable and canonical

SEO Suite 3.1.0
==============
- Full refactoring for MODX3 #67

SEO Suite 3.0.5
==============
- Fix changefreq values #60
- Render meta tags on resources created before seosuit was installed #63
- Make sure redirects are 301 by default #73
- Fix error when user have no access to some context #73
- Disable seoTab in install #73

SEO Suite 3.0.4
==============
- Add buttons `Suggestions excludes` and `Logging excludes`

SEO Suite 3.0.3
==============
- Fix blocked_words usage

SEO Suite 3.0.2
==============
- Fix hreflang attribute in alternate tag

SEO Suite 3.0.1
==============
- Fix sorting in CMP
- Fix prority in sitemap

SEO Suite 3.0.0
==============
- Fix MODX 3 compatibility

SEO Suite 2.0.6
==============
- Fix creating redirect when sorting within same parent
- Fixing sitemap settings save on resource tabs
- Fix 500 error when no resource is found

SEO Suite 2.0.5
==============
- Automatically add a 301 redirect when a resource is moved

SEO Suite 2.0.4
==============
- Fix wrong image URL in custom media source #35

SEO Suite 2.0.3
==============
- Skip arrays to avoid tons message in the logs #15
- Fix displaying meta keywords #21
- Replace attribute name to property for og:-metafields #25
- Add russian lexicon #28

SEO Suite 2.0.2
==============
- Fixed issue which caused rich text content fields to break #4 #5

SEO Suite 2.0.1
==============
- Fixed issue which didn't set the alternate placeholders properly
- Fixed keyword counter issue in combination with Ace
- Fixed issue which didn't save the new url when creating a new redirect
- Fixed incorrect formatted URL during SEO Tab migration
- Added system setting for marking alternate link as x-default

SEO Suite 2.0.0
==============
- Combined SEO Tab, SEO Pro and SEO Suite v1 into one powerful extra
- Added a dedicated SEO panel
- Added Social tab where OG and Twitter meta tags can be managed
- Improved search engine preview

SEO Suite 1.2.3
==============
- Removed license check

SEO Suite 1.2.2
==============
- Added some missing Dutch translations
- Fixed issue with incorrect redirect-cleanup script path
- Improved Dutch/English descriptions

SEO Suite 1.2.1
==============
- validate URL's before saving them
- Able to block URL's from being saved as redirect by system setting

SEO Suite 1.2.0
==============
- Added redirect created date
- Added redirect triggerd count & last time triggerd date
- Added cleanup cronjob which removes unresolved redirects which are older then 1 month and have been triggered just once

SEO Suite 1.1.2
==============
- Added indexes for improved performance

SEO Suite 1.1.1
==============
- Modstore/modmore compatibility

SEO Suite 1.1.0
==============
- Add limit to redirect suggestions shown in grid
- Add SeoSuiteUrl and try to find matches when OnPageNotFound is triggered and no SeoSuiteUrl object is found
- Add dashboard widget with 10 latest SeoSuite URLs
- Detect CSV file delimiter on import
- Add option to limit matches to related context of URL
- Update find suggestions method to add redirect when one match is found
- Add search by ID to resource combobox
- Add system setting (and cmp field) for excluding words from suggestion matching
- Add suggestions combobox to update url window

SEO Suite 1.0.1
==============
- Fix find-suggestions response message to notify if more than one redirect match
- Fix getSeoTabVersion function to check for correct package_name
- Fix grid getlist to show only first 10 redirect suggestions to prevent processor timeouts
- Fix url update processor to not break when not using SEO Tab as redirect handler

SEO Suite 1.0.0
==============
- Initial release.
