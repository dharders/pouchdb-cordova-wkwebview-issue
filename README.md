# pouchdb-cordova-wkwebview-issue

Repro project for pouchdb issue https://github.com/pouchdb/pouchdb/issues/5417

iOS only. Cordova + Sqlite 2 plugin, WKWebView and PouchDB

**Instructions**

```
git clone https://github.com/dharders/pouchdb-cordova-wkwebview-issue.git
cd pouchdb-cordova-wkwebview-issue
cordova prepare
cordova emulate ios

// or
cordova run ios 
```

Note: Assumes cordova is already installed.   sudo npm install -g cordova      (my version is 6.2.0)