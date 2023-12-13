![Bacula-Web dashboard](https://www.bacula-web.org/bacula-web-dashboard.png)

Bacula-Web is a web based tool written in [PHP](https://php.net) which provides a summarized view of your [Bacula](https://www.bacula.org) backup infrastructure.

All the metrics and information provided by Bacula-Web are taken from [Bacula](https://www.bacula.org) catalog database, so there's no need to set up bconsole, bvfs, etc

In addition, the accesses to the database are made read-only, so your Bacula catalog is not altered by Bacula-Web
