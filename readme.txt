=== BoldGrid Staging ===
Contributors: imh_brad, joemoto, rramo012, timph
Tags: inspiration,customization,build,create,design,staging
Requires at least: 4.3
Tested up to: 4.4.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

BoldGrid Staging is a standalone plugin to allow use of a staged website while keeping a live website intact during development.

== Description ==

BoldGrid Staging is a standalone plugin to allow use of a staged website while keeping a live website intact during development.

== Installation ==

1. Upload the entire boldgrid-staging folder to the /wp-content/plugins/ directory.

2. Activate the plugin through the Plugins menu in WordPress.

== Changelog ==

= 1.0.8 =
* Bug fix:		JIRA WPB-1604	Updated some CSS for standards.

= 1.0.7 =
* Bug fix:		JIRA WPB-1634	Now does not enable staging theme on install; use the enable link.
* Rework:		JIRA WPB-1620	Updated require and include statements for standards.
* New feature:	JIRA WPB-1538	Added a way to set staging site's homepage.

= 1.0.6 =
* New feature:	JIRA WPB-1580	Added feedback when deploying a staged site.
* New feature:	JIRA WPB-1572	Added staging switch for static gridblocks

= 1.0.5.1 =
* Bug fix:		JIRA WPB-1553	Fixed PHP version check condition (<5.3).

= 1.0.5 =
* Bug fix:		JIRA WPB-1553	Added support for __DIR__ in PHP <=5.2.
* New feature	JIRA WPB-1542	Manage menu assignment within editor.
* Misc:			JIRA WPB-1468	Updated readme.txt for Tested up to: 4.4.1

= 1.0.4 =
* Bug fix:		JIRA WPB-1426	When installing into staging, with active site, active widgets are overwritten..
* Bug fix:		JIRA WPB-1452	Upon deploying staging, new active sites lost Social Media icons.
* Bug fix:		JIRA WPB-1450	Staging pages show in search results when searing on the front end.

= 1.0.3 =
* Bug fix:		JIRA WPB-1422	Customize links showing in wrong menu...
* New feature	JIRA WPB-1439	Tie into Theme Framework's filter for creating attribution page link and fix it for Staging.
* Bug fix:	JIRA WPB-1428   Live Preview of staged theme throws JS error.
* Bug fix:		JIRA WPB-1446	Properly rename a staged page when it ends with '-staging-(a number)'

= 1.0.2 =
* New feature:	JIRA WPB-1363	Updated readme.txt for WordPress standards.
* Bug Fix:		JIRA WPB-1396	Call to action disappears when customizing staging.
* Bug Fix:		JIRA WPB-1389	Setting Launched staging theme mods to allow theme to trigger activation

= 1.0.1 =
* Rework:						Created class Boldgrid_Staging_Dashboard_Menus and reorganized related code.
* Bug Fix:		JIRA WPB-1383   Fixing issue that prevented color palettes from updating on staging deploy.

= 1.0 =
* Initial public release.

== Upgrade Notice ==

= 1.0.1 =
Users should upgrade to version 1.0.1 to receive a fix for color palettes in staging deployment.