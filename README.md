gcpwiki
========

GCPWiki is an edited Google Appengine Wiki demo

GCPWiki is built based on BGAEWiki which is on top of [GaeWiki](https://github.com/BauweBijl/gaewiki) where, in addition to the upgrade for current Appengine with Python 2.7, Bootstrap is used as frontend.

Install
=======

    cd gcpwiki
    gcloud config set project <your-gae-project>
    gcloud app deploy index.yaml app.yaml

License
=======

The wiki itself is distributed under GNU GPL v3.

pytz is distributed under the MIT license.
