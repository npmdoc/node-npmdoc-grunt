# api documentation for  [grunt (v1.0.1)](http://gruntjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt)
#### The JavaScript Task Runner

[![NPM](https://nodei.co/npm/grunt.png?downloads=true)](https://www.npmjs.com/package/grunt)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-grunt_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Grunt Development Team",
        "url": "http://gruntjs.com/development-team"
    },
    "bin": {
        "grunt": "bin/grunt"
    },
    "bugs": {
        "url": "https://github.com/gruntjs/grunt/issues"
    },
    "contributors": [
        {
            "name": "\"Cowboy\" Ben Alman",
            "url": "http://benalman.com/"
        },
        {
            "name": "Kyle Robinson Young",
            "url": "http://dontkry.com/"
        },
        {
            "name": "Tyler Kellen",
            "url": "http://goingslowly.com"
        },
        {
            "name": "Sindre Sorhus",
            "url": "http://sindresorhus.com"
        },
        {
            "name": "Vlad Filippov",
            "url": "http://vladfilippov.com/"
        }
    ],
    "dependencies": {
        "coffee-script": "~1.10.0",
        "dateformat": "~1.0.12",
        "eventemitter2": "~0.4.13",
        "exit": "~0.1.1",
        "findup-sync": "~0.3.0",
        "glob": "~7.0.0",
        "grunt-cli": "~1.2.0",
        "grunt-known-options": "~1.1.0",
        "grunt-legacy-log": "~1.0.0",
        "grunt-legacy-util": "~1.0.0",
        "iconv-lite": "~0.4.13",
        "js-yaml": "~3.5.2",
        "minimatch": "~3.0.0",
        "nopt": "~3.0.6",
        "path-is-absolute": "~1.0.0",
        "rimraf": "~2.2.8"
    },
    "description": "The JavaScript Task Runner",
    "devDependencies": {
        "difflet": "~0.2.3",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-nodeunit": "~0.4.1",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-jscs": "~2.8.0",
        "semver": "2.1.0",
        "shelljs": "~0.5.3",
        "temporary": "~0.0.4",
        "through2": "~2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e8778764e944b18f32bb0f10b9078475c9dfb56b",
        "tarball": "https://registry.npmjs.org/grunt/-/grunt-1.0.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "lib",
        "bin"
    ],
    "gitHead": "8ada4948b69c6ec9b1e956b5e6b2e6814fa054ca",
    "homepage": "http://gruntjs.com/",
    "keywords": [
        "task",
        "async",
        "cli",
        "minify",
        "uglify",
        "build",
        "lodash",
        "unit",
        "test",
        "qunit",
        "nodeunit",
        "server",
        "init",
        "scaffold",
        "make",
        "jake",
        "tool"
    ],
    "license": "MIT",
    "main": "lib/grunt",
    "maintainers": [
        {
            "name": "cowboy",
            "email": "cowboy@rj3.net"
        },
        {
            "name": "shama",
            "email": "kyle@dontkry.com"
        },
        {
            "name": "tkellen",
            "email": "tyler@sleekcode.net"
        },
        {
            "name": "vladikoff",
            "email": "vlad@vladikoff.com"
        }
    ],
    "name": "grunt",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gruntjs/grunt.git"
    },
    "scripts": {
        "test": "grunt test",
        "test-tap": "grunt test:tap"
    },
    "version": "1.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module grunt](#apidoc.module.grunt)
1.  [function <span class="apidocSignatureSpan">grunt.</span>cli (options, done)](#apidoc.element.grunt.cli)
1.  [function <span class="apidocSignatureSpan">grunt.</span>config (prop, value)](#apidoc.element.grunt.config)
1.  [function <span class="apidocSignatureSpan">grunt.</span>fatal ()](#apidoc.element.grunt.fatal)
1.  [function <span class="apidocSignatureSpan">grunt.</span>file.glob (pattern, options, cb)](#apidoc.element.grunt.file.glob)
1.  [function <span class="apidocSignatureSpan">grunt.</span>file.minimatch (p, pattern, options)](#apidoc.element.grunt.file.minimatch)
1.  [function <span class="apidocSignatureSpan">grunt.</span>initConfig ()](#apidoc.element.grunt.initConfig)
1.  [function <span class="apidocSignatureSpan">grunt.</span>loadNpmTasks ()](#apidoc.element.grunt.loadNpmTasks)
1.  [function <span class="apidocSignatureSpan">grunt.</span>loadTasks ()](#apidoc.element.grunt.loadTasks)
1.  [function <span class="apidocSignatureSpan">grunt.</span>option (key, value)](#apidoc.element.grunt.option)
1.  [function <span class="apidocSignatureSpan">grunt.</span>registerInitTask ()](#apidoc.element.grunt.registerInitTask)
1.  [function <span class="apidocSignatureSpan">grunt.</span>registerMultiTask ()](#apidoc.element.grunt.registerMultiTask)
1.  [function <span class="apidocSignatureSpan">grunt.</span>registerTask ()](#apidoc.element.grunt.registerTask)
1.  [function <span class="apidocSignatureSpan">grunt.</span>renameTask ()](#apidoc.element.grunt.renameTask)
1.  [function <span class="apidocSignatureSpan">grunt.</span>tasks (tasks, options, done)](#apidoc.element.grunt.tasks)
1.  function <span class="apidocSignatureSpan">grunt.</span>util._
1.  [function <span class="apidocSignatureSpan">grunt.</span>warn ()](#apidoc.element.grunt.warn)
1.  object <span class="apidocSignatureSpan">grunt.</span>event
1.  object <span class="apidocSignatureSpan">grunt.</span>fail
1.  object <span class="apidocSignatureSpan">grunt.</span>file
1.  object <span class="apidocSignatureSpan">grunt.</span>file.glob.Glob.prototype
1.  object <span class="apidocSignatureSpan">grunt.</span>file.glob.GlobSync.prototype
1.  object <span class="apidocSignatureSpan">grunt.</span>file.minimatch.Minimatch.prototype
1.  object <span class="apidocSignatureSpan">grunt.</span>help
1.  object <span class="apidocSignatureSpan">grunt.</span>log
1.  object <span class="apidocSignatureSpan">grunt.</span>log.notverbose
1.  object <span class="apidocSignatureSpan">grunt.</span>package
1.  object <span class="apidocSignatureSpan">grunt.</span>task
1.  object <span class="apidocSignatureSpan">grunt.</span>template
1.  object <span class="apidocSignatureSpan">grunt.</span>util
1.  object <span class="apidocSignatureSpan">grunt.</span>util._.prototype
1.  object <span class="apidocSignatureSpan">grunt.</span>util._.str.prototype
1.  object <span class="apidocSignatureSpan">grunt.</span>util.async
1.  object <span class="apidocSignatureSpan">grunt.</span>util.hooker
1.  object <span class="apidocSignatureSpan">grunt.</span>util.namespace
1.  object <span class="apidocSignatureSpan">grunt.</span>util.task
1.  object <span class="apidocSignatureSpan">grunt.</span>util.task.Task.prototype
1.  object <span class="apidocSignatureSpan">grunt.</span>verbose
1.  string <span class="apidocSignatureSpan">grunt.</span>version

#### [module grunt.config](#apidoc.module.grunt.config)
1.  [function <span class="apidocSignatureSpan">grunt.</span>config (prop, value)](#apidoc.element.grunt.config.config)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>escape (str)](#apidoc.element.grunt.config.escape)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>get (prop)](#apidoc.element.grunt.config.get)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>getPropString (prop)](#apidoc.element.grunt.config.getPropString)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>getRaw (prop)](#apidoc.element.grunt.config.getRaw)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>init (obj)](#apidoc.element.grunt.config.init)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>merge (obj)](#apidoc.element.grunt.config.merge)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>process (raw)](#apidoc.element.grunt.config.process)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>requires ()](#apidoc.element.grunt.config.requires)
1.  [function <span class="apidocSignatureSpan">grunt.config.</span>set (prop, value)](#apidoc.element.grunt.config.set)
1.  object <span class="apidocSignatureSpan">grunt.config.</span>data

#### [module grunt.fail](#apidoc.module.grunt.fail)
1.  [function <span class="apidocSignatureSpan">grunt.fail.</span>fatal (e, errcode)](#apidoc.element.grunt.fail.fatal)
1.  [function <span class="apidocSignatureSpan">grunt.fail.</span>report ()](#apidoc.element.grunt.fail.report)
1.  [function <span class="apidocSignatureSpan">grunt.fail.</span>warn (e, errcode)](#apidoc.element.grunt.fail.warn)
1.  number <span class="apidocSignatureSpan">grunt.fail.</span>errorcount
1.  number <span class="apidocSignatureSpan">grunt.fail.</span>warncount
1.  object <span class="apidocSignatureSpan">grunt.fail.</span>code

#### [module grunt.file](#apidoc.module.grunt.file)
1.  boolean <span class="apidocSignatureSpan">grunt.file.</span>preserveBOM
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>_copy (srcpath, destpath, options)](#apidoc.element.grunt.file._copy)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>arePathsEquivalent (first)](#apidoc.element.grunt.file.arePathsEquivalent)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>copy (srcpath, destpath, options)](#apidoc.element.grunt.file.copy)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>delete (filepath, options)](#apidoc.element.grunt.file.delete)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>doesPathContain (ancestor)](#apidoc.element.grunt.file.doesPathContain)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>exists ()](#apidoc.element.grunt.file.exists)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>expand ()](#apidoc.element.grunt.file.expand)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>expandMapping (patterns, destBase, options)](#apidoc.element.grunt.file.expandMapping)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>findup (patterns, options)](#apidoc.element.grunt.file.findup)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>glob (pattern, options, cb)](#apidoc.element.grunt.file.glob)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>isDir ()](#apidoc.element.grunt.file.isDir)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>isFile ()](#apidoc.element.grunt.file.isFile)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>isLink ()](#apidoc.element.grunt.file.isLink)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>isMatch ()](#apidoc.element.grunt.file.isMatch)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>isPathAbsolute ()](#apidoc.element.grunt.file.isPathAbsolute)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>isPathCwd ()](#apidoc.element.grunt.file.isPathCwd)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>isPathInCwd ()](#apidoc.element.grunt.file.isPathInCwd)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>match (options, patterns, filepaths)](#apidoc.element.grunt.file.match)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>minimatch (p, pattern, options)](#apidoc.element.grunt.file.minimatch)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>mkdir (dirpath, mode)](#apidoc.element.grunt.file.mkdir)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>read (filepath, options)](#apidoc.element.grunt.file.read)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>readJSON (filepath, options)](#apidoc.element.grunt.file.readJSON)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>readYAML (filepath, options)](#apidoc.element.grunt.file.readYAML)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>recurse (rootdir, callback, subdir)](#apidoc.element.grunt.file.recurse)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>setBase ()](#apidoc.element.grunt.file.setBase)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>write (filepath, contents, options)](#apidoc.element.grunt.file.write)
1.  string <span class="apidocSignatureSpan">grunt.file.</span>defaultEncoding

#### [module grunt.file.glob](#apidoc.module.grunt.file.glob)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>glob (pattern, options, cb)](#apidoc.element.grunt.file.glob.glob)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.</span>Glob (pattern, options, cb)](#apidoc.element.grunt.file.glob.Glob)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.</span>GlobSync (pattern, options)](#apidoc.element.grunt.file.glob.GlobSync)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.</span>hasMagic (pattern, options_)](#apidoc.element.grunt.file.glob.hasMagic)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.</span>sync (pattern, options)](#apidoc.element.grunt.file.glob.sync)

#### [module grunt.file.glob.Glob.prototype](#apidoc.module.grunt.file.glob.Glob.prototype)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_emitMatch (index, e)](#apidoc.element.grunt.file.glob.Glob.prototype._emitMatch)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_finish ()](#apidoc.element.grunt.file.glob.Glob.prototype._finish)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_makeAbs (f)](#apidoc.element.grunt.file.glob.Glob.prototype._makeAbs)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_mark (p)](#apidoc.element.grunt.file.glob.Glob.prototype._mark)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_process (pattern, index, inGlobStar, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._process)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processGlobStar (prefix, read, abs, remain, index, inGlobStar, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processGlobStar)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processGlobStar2 (prefix, read, abs, remain, index, inGlobStar, entries, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processGlobStar2)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processReaddir (prefix, read, abs, remain, index, inGlobStar, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processReaddir)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processReaddir2 (prefix, read, abs, remain, index, inGlobStar, entries, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processReaddir2)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processSimple (prefix, index, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processSimple)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processSimple2 (prefix, index, er, exists, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processSimple2)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_readdir (abs, inGlobStar, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._readdir)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_readdirEntries (abs, entries, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._readdirEntries)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_readdirError (f, er, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._readdirError)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_readdirInGlobStar (abs, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._readdirInGlobStar)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_realpath ()](#apidoc.element.grunt.file.glob.Glob.prototype._realpath)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_realpathSet (index, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._realpathSet)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_stat (f, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._stat)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_stat2 (f, abs, er, stat, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._stat2)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>abort ()](#apidoc.element.grunt.file.glob.Glob.prototype.abort)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>pause ()](#apidoc.element.grunt.file.glob.Glob.prototype.pause)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>resume ()](#apidoc.element.grunt.file.glob.Glob.prototype.resume)

#### [module grunt.file.glob.GlobSync.prototype](#apidoc.module.grunt.file.glob.GlobSync.prototype)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_emitMatch (index, e)](#apidoc.element.grunt.file.glob.GlobSync.prototype._emitMatch)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_finish ()](#apidoc.element.grunt.file.glob.GlobSync.prototype._finish)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_makeAbs (f)](#apidoc.element.grunt.file.glob.GlobSync.prototype._makeAbs)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_mark (p)](#apidoc.element.grunt.file.glob.GlobSync.prototype._mark)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_process (pattern, index, inGlobStar)](#apidoc.element.grunt.file.glob.GlobSync.prototype._process)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_processGlobStar (prefix, read, abs, remain, index, inGlobStar)](#apidoc.element.grunt.file.glob.GlobSync.prototype._processGlobStar)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_processReaddir (prefix, read, abs, remain, index, inGlobStar)](#apidoc.element.grunt.file.glob.GlobSync.prototype._processReaddir)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_processSimple (prefix, index)](#apidoc.element.grunt.file.glob.GlobSync.prototype._processSimple)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_readdir (abs, inGlobStar)](#apidoc.element.grunt.file.glob.GlobSync.prototype._readdir)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_readdirEntries (abs, entries)](#apidoc.element.grunt.file.glob.GlobSync.prototype._readdirEntries)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_readdirError (f, er)](#apidoc.element.grunt.file.glob.GlobSync.prototype._readdirError)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_readdirInGlobStar (abs)](#apidoc.element.grunt.file.glob.GlobSync.prototype._readdirInGlobStar)
1.  [function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_stat (f)](#apidoc.element.grunt.file.glob.GlobSync.prototype._stat)

#### [module grunt.file.minimatch](#apidoc.module.grunt.file.minimatch)
1.  [function <span class="apidocSignatureSpan">grunt.file.</span>minimatch (p, pattern, options)](#apidoc.element.grunt.file.minimatch.minimatch)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>Minimatch (pattern, options)](#apidoc.element.grunt.file.minimatch.Minimatch)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>braceExpand (pattern, options)](#apidoc.element.grunt.file.minimatch.braceExpand)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>defaults (def)](#apidoc.element.grunt.file.minimatch.defaults)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>filter (pattern, options)](#apidoc.element.grunt.file.minimatch.filter)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>makeRe (pattern, options)](#apidoc.element.grunt.file.minimatch.makeRe)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>match (list, pattern, options)](#apidoc.element.grunt.file.minimatch.match)
1.  object <span class="apidocSignatureSpan">grunt.file.minimatch.</span>GLOBSTAR

#### [module grunt.file.minimatch.Minimatch.prototype](#apidoc.module.grunt.file.minimatch.Minimatch.prototype)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>braceExpand (pattern, options)](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.braceExpand)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>debug ()](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.debug)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>make ()](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.make)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>makeRe ()](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.makeRe)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>match (f, partial)](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.match)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>matchOne (file, pattern, partial)](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.matchOne)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>parse (pattern, isSub)](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.parse)
1.  [function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>parseNegate ()](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.parseNegate)

#### [module grunt.help](#apidoc.module.grunt.help)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>display ()](#apidoc.element.grunt.help.display)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>footer ()](#apidoc.element.grunt.help.footer)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>header ()](#apidoc.element.grunt.help.header)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>initCol1 (str)](#apidoc.element.grunt.help.initCol1)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>initOptions ()](#apidoc.element.grunt.help.initOptions)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>initTasks ()](#apidoc.element.grunt.help.initTasks)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>initWidths ()](#apidoc.element.grunt.help.initWidths)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>options ()](#apidoc.element.grunt.help.options)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>optionsFooter ()](#apidoc.element.grunt.help.optionsFooter)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>table (arr)](#apidoc.element.grunt.help.table)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>tasks ()](#apidoc.element.grunt.help.tasks)
1.  [function <span class="apidocSignatureSpan">grunt.help.</span>usage ()](#apidoc.element.grunt.help.usage)
1.  object <span class="apidocSignatureSpan">grunt.help.</span>queue

#### [module grunt.log](#apidoc.module.grunt.log)
1.  boolean <span class="apidocSignatureSpan">grunt.log.</span>_hasLogged
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>_format ()](#apidoc.element.grunt.log._format)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>_markup ()](#apidoc.element.grunt.log._markup)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>_write ()](#apidoc.element.grunt.log._write)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>_writeln ()](#apidoc.element.grunt.log._writeln)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>debug ()](#apidoc.element.grunt.log.debug)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>error ()](#apidoc.element.grunt.log.error)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>errorlns ()](#apidoc.element.grunt.log.errorlns)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>fail ()](#apidoc.element.grunt.log.fail)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>header ()](#apidoc.element.grunt.log.header)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>initColors ()](#apidoc.element.grunt.log.initColors)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>ok ()](#apidoc.element.grunt.log.ok)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>oklns ()](#apidoc.element.grunt.log.oklns)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>option ()](#apidoc.element.grunt.log.option)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>subhead ()](#apidoc.element.grunt.log.subhead)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>success ()](#apidoc.element.grunt.log.success)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>table ()](#apidoc.element.grunt.log.table)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>uncolor ()](#apidoc.element.grunt.log.uncolor)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>warn ()](#apidoc.element.grunt.log.warn)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>wordlist ()](#apidoc.element.grunt.log.wordlist)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>wraptext ()](#apidoc.element.grunt.log.wraptext)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>write ()](#apidoc.element.grunt.log.write)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>writeflags ()](#apidoc.element.grunt.log.writeflags)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>writeln ()](#apidoc.element.grunt.log.writeln)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>writelns ()](#apidoc.element.grunt.log.writelns)
1.  [function <span class="apidocSignatureSpan">grunt.log.</span>writetableln ()](#apidoc.element.grunt.log.writetableln)
1.  object <span class="apidocSignatureSpan">grunt.log.</span>_options
1.  object <span class="apidocSignatureSpan">grunt.log.</span>always
1.  object <span class="apidocSignatureSpan">grunt.log.</span>notverbose
1.  object <span class="apidocSignatureSpan">grunt.log.</span>verbose

#### [module grunt.log.notverbose](#apidoc.module.grunt.log.notverbose)
1.  boolean <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_isVerbose
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_format ()](#apidoc.element.grunt.log.notverbose._format)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_markup ()](#apidoc.element.grunt.log.notverbose._markup)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_write ()](#apidoc.element.grunt.log.notverbose._write)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_writeln ()](#apidoc.element.grunt.log.notverbose._writeln)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>debug ()](#apidoc.element.grunt.log.notverbose.debug)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>error ()](#apidoc.element.grunt.log.notverbose.error)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>errorlns ()](#apidoc.element.grunt.log.notverbose.errorlns)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>fail ()](#apidoc.element.grunt.log.notverbose.fail)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>header ()](#apidoc.element.grunt.log.notverbose.header)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>initColors ()](#apidoc.element.grunt.log.notverbose.initColors)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>ok ()](#apidoc.element.grunt.log.notverbose.ok)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>oklns ()](#apidoc.element.grunt.log.notverbose.oklns)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>option ()](#apidoc.element.grunt.log.notverbose.option)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>subhead ()](#apidoc.element.grunt.log.notverbose.subhead)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>success ()](#apidoc.element.grunt.log.notverbose.success)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>table ()](#apidoc.element.grunt.log.notverbose.table)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>uncolor ()](#apidoc.element.grunt.log.notverbose.uncolor)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>warn ()](#apidoc.element.grunt.log.notverbose.warn)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>wordlist ()](#apidoc.element.grunt.log.notverbose.wordlist)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>wraptext ()](#apidoc.element.grunt.log.notverbose.wraptext)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>write ()](#apidoc.element.grunt.log.notverbose.write)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>writeflags ()](#apidoc.element.grunt.log.notverbose.writeflags)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>writeln ()](#apidoc.element.grunt.log.notverbose.writeln)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>writelns ()](#apidoc.element.grunt.log.notverbose.writelns)
1.  [function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>writetableln ()](#apidoc.element.grunt.log.notverbose.writetableln)
1.  object <span class="apidocSignatureSpan">grunt.log.notverbose.</span>always
1.  object <span class="apidocSignatureSpan">grunt.log.notverbose.</span>or

#### [module grunt.option](#apidoc.module.grunt.option)
1.  [function <span class="apidocSignatureSpan">grunt.</span>option (key, value)](#apidoc.element.grunt.option.option)
1.  [function <span class="apidocSignatureSpan">grunt.option.</span>flags ()](#apidoc.element.grunt.option.flags)
1.  [function <span class="apidocSignatureSpan">grunt.option.</span>init (obj)](#apidoc.element.grunt.option.init)

#### [module grunt.task](#apidoc.module.grunt.task)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>init (tasks, options)](#apidoc.element.grunt.task.init)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>loadNpmTasks (name)](#apidoc.element.grunt.task.loadNpmTasks)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>loadTasks (tasksdir)](#apidoc.element.grunt.task.loadTasks)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>normalizeMultiTaskFiles (data, target)](#apidoc.element.grunt.task.normalizeMultiTaskFiles)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>registerInitTask (name, info, fn)](#apidoc.element.grunt.task.registerInitTask)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>registerMultiTask (name, info, fn)](#apidoc.element.grunt.task.registerMultiTask)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>registerTask (name)](#apidoc.element.grunt.task.registerTask)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>renameTask (oldname, newname)](#apidoc.element.grunt.task.renameTask)
1.  [function <span class="apidocSignatureSpan">grunt.task.</span>runAllTargets (taskname, args)](#apidoc.element.grunt.task.runAllTargets)

#### [module grunt.template](#apidoc.module.grunt.template)
1.  [function <span class="apidocSignatureSpan">grunt.template.</span>addDelimiters (name, opener, closer)](#apidoc.element.grunt.template.addDelimiters)
1.  [function <span class="apidocSignatureSpan">grunt.template.</span>date (date, mask, utc, gmt)](#apidoc.element.grunt.template.date)
1.  [function <span class="apidocSignatureSpan">grunt.template.</span>process (tmpl, options)](#apidoc.element.grunt.template.process)
1.  [function <span class="apidocSignatureSpan">grunt.template.</span>setDelimiters (name)](#apidoc.element.grunt.template.setDelimiters)
1.  [function <span class="apidocSignatureSpan">grunt.template.</span>today (format)](#apidoc.element.grunt.template.today)

#### [module grunt.util](#apidoc.module.grunt.util)
1.  function <span class="apidocSignatureSpan">grunt.util.</span>_
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>callbackify (fn)](#apidoc.element.grunt.util.callbackify)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>error (err, origError)](#apidoc.element.grunt.util.error)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>exit (exitCode, streams)](#apidoc.element.grunt.util.exit)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>kindOf (value)](#apidoc.element.grunt.util.kindOf)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>normalizelf (str)](#apidoc.element.grunt.util.normalizelf)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>pluralize (n, str, separator)](#apidoc.element.grunt.util.pluralize)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>recurse (value, fn, fnContinue)](#apidoc.element.grunt.util.recurse)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>repeat (n, str)](#apidoc.element.grunt.util.repeat)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>spawn (opts, done)](#apidoc.element.grunt.util.spawn)
1.  [function <span class="apidocSignatureSpan">grunt.util.</span>toArray (value)](#apidoc.element.grunt.util.toArray)
1.  object <span class="apidocSignatureSpan">grunt.util.</span>async
1.  object <span class="apidocSignatureSpan">grunt.util.</span>hooker
1.  object <span class="apidocSignatureSpan">grunt.util.</span>namespace
1.  object <span class="apidocSignatureSpan">grunt.util.</span>task
1.  string <span class="apidocSignatureSpan">grunt.util.</span>linefeed

#### [module grunt.util._](#apidoc.module.grunt.util._)
1.  function <span class="apidocSignatureSpan">grunt.util.</span>_
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>add (augend, addend)](#apidoc.element.grunt.util._.add)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>after (n, func)](#apidoc.element.grunt.util._.after)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>ary (func, n, guard)](#apidoc.element.grunt.util._.ary)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>assign ()](#apidoc.element.grunt.util._.assign)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>assignIn ()](#apidoc.element.grunt.util._.assignIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>assignInWith ()](#apidoc.element.grunt.util._.assignInWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>assignWith ()](#apidoc.element.grunt.util._.assignWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>at ()](#apidoc.element.grunt.util._.at)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>attempt ()](#apidoc.element.grunt.util._.attempt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>before (n, func)](#apidoc.element.grunt.util._.before)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>bind ()](#apidoc.element.grunt.util._.bind)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>bindAll ()](#apidoc.element.grunt.util._.bindAll)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>bindKey ()](#apidoc.element.grunt.util._.bindKey)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>camelCase (string)](#apidoc.element.grunt.util._.camelCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>camelcase (str, decapitalize)](#apidoc.element.grunt.util._.camelcase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>camelize (str, decapitalize)](#apidoc.element.grunt.util._.camelize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>capitalize (str, lowercaseRest)](#apidoc.element.grunt.util._.capitalize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>ceil (number, precision)](#apidoc.element.grunt.util._.ceil)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>center (str, length, padStr)](#apidoc.element.grunt.util._.center)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>chain (value)](#apidoc.element.grunt.util._.chain)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>chars (str)](#apidoc.element.grunt.util._.chars)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>chop (str, step)](#apidoc.element.grunt.util._.chop)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>chunk (array, size)](#apidoc.element.grunt.util._.chunk)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>clamp (number, lower, upper)](#apidoc.element.grunt.util._.clamp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>classify (str)](#apidoc.element.grunt.util._.classify)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>clean (str)](#apidoc.element.grunt.util._.clean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>cleanDiacritics (str)](#apidoc.element.grunt.util._.cleanDiacritics)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>clone (value)](#apidoc.element.grunt.util._.clone)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>cloneDeep (value)](#apidoc.element.grunt.util._.cloneDeep)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>cloneDeepWith (value, customizer)](#apidoc.element.grunt.util._.cloneDeepWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>cloneWith (value, customizer)](#apidoc.element.grunt.util._.cloneWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>compact (array)](#apidoc.element.grunt.util._.compact)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>concat ()](#apidoc.element.grunt.util._.concat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>cond (pairs)](#apidoc.element.grunt.util._.cond)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>conforms (source)](#apidoc.element.grunt.util._.conforms)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>constant (value)](#apidoc.element.grunt.util._.constant)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>count (str, substr)](#apidoc.element.grunt.util._.count)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>countBy (collection, iteratee)](#apidoc.element.grunt.util._.countBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>create (prototype, properties)](#apidoc.element.grunt.util._.create)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>curry (func, arity, guard)](#apidoc.element.grunt.util._.curry)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>curryRight (func, arity, guard)](#apidoc.element.grunt.util._.curryRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>dasherize (str)](#apidoc.element.grunt.util._.dasherize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>debounce (func, wait, options)](#apidoc.element.grunt.util._.debounce)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>deburr (string)](#apidoc.element.grunt.util._.deburr)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>decapitalize (str)](#apidoc.element.grunt.util._.decapitalize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>dedent (str, pattern)](#apidoc.element.grunt.util._.dedent)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>defaults ()](#apidoc.element.grunt.util._.defaults)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>defaultsDeep ()](#apidoc.element.grunt.util._.defaultsDeep)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>defer ()](#apidoc.element.grunt.util._.defer)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>delay ()](#apidoc.element.grunt.util._.delay)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>difference ()](#apidoc.element.grunt.util._.difference)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>differenceBy ()](#apidoc.element.grunt.util._.differenceBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>differenceWith ()](#apidoc.element.grunt.util._.differenceWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>drop (array, n, guard)](#apidoc.element.grunt.util._.drop)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>dropRight (array, n, guard)](#apidoc.element.grunt.util._.dropRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>dropRightWhile (array, predicate)](#apidoc.element.grunt.util._.dropRightWhile)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>dropWhile (array, predicate)](#apidoc.element.grunt.util._.dropWhile)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>each (collection, iteratee)](#apidoc.element.grunt.util._.each)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>eachRight (collection, iteratee)](#apidoc.element.grunt.util._.eachRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>endsWith (str, ends, position)](#apidoc.element.grunt.util._.endsWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>eq (value, other)](#apidoc.element.grunt.util._.eq)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>escape (string)](#apidoc.element.grunt.util._.escape)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>escapeHTML (str)](#apidoc.element.grunt.util._.escapeHTML)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>escapeRegExp (str)](#apidoc.element.grunt.util._.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>every (collection, predicate, guard)](#apidoc.element.grunt.util._.every)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>exports ()](#apidoc.element.grunt.util._.exports)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>extend ()](#apidoc.element.grunt.util._.extend)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>extendWith ()](#apidoc.element.grunt.util._.extendWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>fill (array, value, start, end)](#apidoc.element.grunt.util._.fill)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>filter (collection, predicate)](#apidoc.element.grunt.util._.filter)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>find (collection, predicate)](#apidoc.element.grunt.util._.find)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>findIndex (array, predicate)](#apidoc.element.grunt.util._.findIndex)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>findKey (object, predicate)](#apidoc.element.grunt.util._.findKey)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>findLast (collection, predicate)](#apidoc.element.grunt.util._.findLast)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>findLastIndex (array, predicate)](#apidoc.element.grunt.util._.findLastIndex)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>findLastKey (object, predicate)](#apidoc.element.grunt.util._.findLastKey)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>first (array)](#apidoc.element.grunt.util._.first)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>flatMap (collection, iteratee)](#apidoc.element.grunt.util._.flatMap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>flatten (array)](#apidoc.element.grunt.util._.flatten)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>flattenDeep (array)](#apidoc.element.grunt.util._.flattenDeep)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>flip (func)](#apidoc.element.grunt.util._.flip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>floor (number, precision)](#apidoc.element.grunt.util._.floor)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>flow ()](#apidoc.element.grunt.util._.flow)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>flowRight ()](#apidoc.element.grunt.util._.flowRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>forEach (collection, iteratee)](#apidoc.element.grunt.util._.forEach)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>forEachRight (collection, iteratee)](#apidoc.element.grunt.util._.forEachRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>forIn (object, iteratee)](#apidoc.element.grunt.util._.forIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>forInRight (object, iteratee)](#apidoc.element.grunt.util._.forInRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>forOwn (object, iteratee)](#apidoc.element.grunt.util._.forOwn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>forOwnRight (object, iteratee)](#apidoc.element.grunt.util._.forOwnRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>fromPairs (pairs)](#apidoc.element.grunt.util._.fromPairs)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>functions (object)](#apidoc.element.grunt.util._.functions)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>functionsIn (object)](#apidoc.element.grunt.util._.functionsIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>get (object, path, defaultValue)](#apidoc.element.grunt.util._.get)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>groupBy (collection, iteratee)](#apidoc.element.grunt.util._.groupBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>gt (value, other)](#apidoc.element.grunt.util._.gt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>gte (value, other)](#apidoc.element.grunt.util._.gte)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>has (object, path)](#apidoc.element.grunt.util._.has)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>hasIn (object, path)](#apidoc.element.grunt.util._.hasIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>head (array)](#apidoc.element.grunt.util._.head)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>humanize (str)](#apidoc.element.grunt.util._.humanize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>identity (value)](#apidoc.element.grunt.util._.identity)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>inRange (number, start, end)](#apidoc.element.grunt.util._.inRange)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>includes (collection, value, fromIndex, guard)](#apidoc.element.grunt.util._.includes)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>indexOf (array, value, fromIndex)](#apidoc.element.grunt.util._.indexOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>initial (array)](#apidoc.element.grunt.util._.initial)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>insert (str, i, substr)](#apidoc.element.grunt.util._.insert)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>intersection ()](#apidoc.element.grunt.util._.intersection)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>intersectionBy ()](#apidoc.element.grunt.util._.intersectionBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>intersectionWith ()](#apidoc.element.grunt.util._.intersectionWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>invert (object, iteratee)](#apidoc.element.grunt.util._.invert)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>invertBy (object, iteratee)](#apidoc.element.grunt.util._.invertBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>invoke ()](#apidoc.element.grunt.util._.invoke)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>invokeMap ()](#apidoc.element.grunt.util._.invokeMap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isArguments (value)](#apidoc.element.grunt.util._.isArguments)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isArray ()](#apidoc.element.grunt.util._.isArray)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isArrayBuffer (value)](#apidoc.element.grunt.util._.isArrayBuffer)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isArrayLike (value)](#apidoc.element.grunt.util._.isArrayLike)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isArrayLikeObject (value)](#apidoc.element.grunt.util._.isArrayLikeObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isBlank (str)](#apidoc.element.grunt.util._.isBlank)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isBoolean (value)](#apidoc.element.grunt.util._.isBoolean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isBuffer (value)](#apidoc.element.grunt.util._.isBuffer)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isDate (value)](#apidoc.element.grunt.util._.isDate)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isElement (value)](#apidoc.element.grunt.util._.isElement)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isEmpty (value)](#apidoc.element.grunt.util._.isEmpty)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isEqual (value, other)](#apidoc.element.grunt.util._.isEqual)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isEqualWith (value, other, customizer)](#apidoc.element.grunt.util._.isEqualWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isError (value)](#apidoc.element.grunt.util._.isError)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isFinite (value)](#apidoc.element.grunt.util._.isFinite)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isFunction (value)](#apidoc.element.grunt.util._.isFunction)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isInteger (value)](#apidoc.element.grunt.util._.isInteger)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isLength (value)](#apidoc.element.grunt.util._.isLength)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isMap (value)](#apidoc.element.grunt.util._.isMap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isMatch (object, source)](#apidoc.element.grunt.util._.isMatch)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isMatchWith (object, source, customizer)](#apidoc.element.grunt.util._.isMatchWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isNaN (value)](#apidoc.element.grunt.util._.isNaN)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isNative (value)](#apidoc.element.grunt.util._.isNative)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isNil (value)](#apidoc.element.grunt.util._.isNil)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isNull (value)](#apidoc.element.grunt.util._.isNull)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isNumber (value)](#apidoc.element.grunt.util._.isNumber)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isObject (value)](#apidoc.element.grunt.util._.isObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isObjectLike (value)](#apidoc.element.grunt.util._.isObjectLike)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isPlainObject (value)](#apidoc.element.grunt.util._.isPlainObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isRegExp (value)](#apidoc.element.grunt.util._.isRegExp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isSafeInteger (value)](#apidoc.element.grunt.util._.isSafeInteger)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isSet (value)](#apidoc.element.grunt.util._.isSet)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isString (value)](#apidoc.element.grunt.util._.isString)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isSymbol (value)](#apidoc.element.grunt.util._.isSymbol)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isTypedArray (value)](#apidoc.element.grunt.util._.isTypedArray)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isUndefined (value)](#apidoc.element.grunt.util._.isUndefined)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isWeakMap (value)](#apidoc.element.grunt.util._.isWeakMap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>isWeakSet (value)](#apidoc.element.grunt.util._.isWeakSet)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>iteratee (func)](#apidoc.element.grunt.util._.iteratee)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>join (array, separator)](#apidoc.element.grunt.util._.join)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>kebabCase (string)](#apidoc.element.grunt.util._.kebabCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>keyBy (collection, iteratee)](#apidoc.element.grunt.util._.keyBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>keys (object)](#apidoc.element.grunt.util._.keys)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>keysIn (object)](#apidoc.element.grunt.util._.keysIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>last (array)](#apidoc.element.grunt.util._.last)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.grunt.util._.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>levenshtein (str1, str2)](#apidoc.element.grunt.util._.levenshtein)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lines (str)](#apidoc.element.grunt.util._.lines)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>ljust (str, length, padStr)](#apidoc.element.grunt.util._.ljust)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lowerCase (string)](#apidoc.element.grunt.util._.lowerCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lowerFirst (string)](#apidoc.element.grunt.util._.lowerFirst)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lpad (str, length, padStr)](#apidoc.element.grunt.util._.lpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lrpad (str, length, padStr)](#apidoc.element.grunt.util._.lrpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lstrip (str, characters)](#apidoc.element.grunt.util._.lstrip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lt (value, other)](#apidoc.element.grunt.util._.lt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>lte (value, other)](#apidoc.element.grunt.util._.lte)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>ltrim (str, characters)](#apidoc.element.grunt.util._.ltrim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>map (collection, iteratee)](#apidoc.element.grunt.util._.map)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>mapChars (str, callback)](#apidoc.element.grunt.util._.mapChars)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>mapKeys (object, iteratee)](#apidoc.element.grunt.util._.mapKeys)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>mapValues (object, iteratee)](#apidoc.element.grunt.util._.mapValues)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>matches (source)](#apidoc.element.grunt.util._.matches)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>matchesProperty (path, srcValue)](#apidoc.element.grunt.util._.matchesProperty)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>max (array)](#apidoc.element.grunt.util._.max)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>maxBy (array, iteratee)](#apidoc.element.grunt.util._.maxBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>mean (array)](#apidoc.element.grunt.util._.mean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>memoize (func, resolver)](#apidoc.element.grunt.util._.memoize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>merge ()](#apidoc.element.grunt.util._.merge)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>mergeWith ()](#apidoc.element.grunt.util._.mergeWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>method ()](#apidoc.element.grunt.util._.method)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>methodOf ()](#apidoc.element.grunt.util._.methodOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>min (array)](#apidoc.element.grunt.util._.min)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>minBy (array, iteratee)](#apidoc.element.grunt.util._.minBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>mixin (object, source, options)](#apidoc.element.grunt.util._.mixin)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>naturalCmp (str1, str2)](#apidoc.element.grunt.util._.naturalCmp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>negate (predicate)](#apidoc.element.grunt.util._.negate)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>noConflict ()](#apidoc.element.grunt.util._.noConflict)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>noop ()](#apidoc.element.grunt.util._.noop)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>now ()](#apidoc.element.grunt.util._.now)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>nthArg (n)](#apidoc.element.grunt.util._.nthArg)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>numberFormat (number, dec, dsep, tsep)](#apidoc.element.grunt.util._.numberFormat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>omit ()](#apidoc.element.grunt.util._.omit)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>omitBy (object, predicate)](#apidoc.element.grunt.util._.omitBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>once (func)](#apidoc.element.grunt.util._.once)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>orderBy (collection, iteratees, orders, guard)](#apidoc.element.grunt.util._.orderBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>over ()](#apidoc.element.grunt.util._.over)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>overArgs ()](#apidoc.element.grunt.util._.overArgs)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>overEvery ()](#apidoc.element.grunt.util._.overEvery)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>overSome ()](#apidoc.element.grunt.util._.overSome)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>pad (str, length, padStr, type)](#apidoc.element.grunt.util._.pad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>padEnd (string, length, chars)](#apidoc.element.grunt.util._.padEnd)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>padStart (string, length, chars)](#apidoc.element.grunt.util._.padStart)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>parseInt (string, radix, guard)](#apidoc.element.grunt.util._.parseInt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>partial ()](#apidoc.element.grunt.util._.partial)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>partialRight ()](#apidoc.element.grunt.util._.partialRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>partition (collection, iteratee)](#apidoc.element.grunt.util._.partition)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>pick ()](#apidoc.element.grunt.util._.pick)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>pickBy (object, predicate)](#apidoc.element.grunt.util._.pickBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>pred (str)](#apidoc.element.grunt.util._.pred)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>property (path)](#apidoc.element.grunt.util._.property)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>propertyOf (object)](#apidoc.element.grunt.util._.propertyOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>prune (str, length, pruneStr)](#apidoc.element.grunt.util._.prune)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>pull ()](#apidoc.element.grunt.util._.pull)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>pullAll (array, values)](#apidoc.element.grunt.util._.pullAll)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>pullAllBy (array, values, iteratee)](#apidoc.element.grunt.util._.pullAllBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>pullAt ()](#apidoc.element.grunt.util._.pullAt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>q (str, quoteChar)](#apidoc.element.grunt.util._.q)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>quote (str, quoteChar)](#apidoc.element.grunt.util._.quote)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>random (lower, upper, floating)](#apidoc.element.grunt.util._.random)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>range (start, end, step)](#apidoc.element.grunt.util._.range)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>rangeRight (start, end, step)](#apidoc.element.grunt.util._.rangeRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>rearg ()](#apidoc.element.grunt.util._.rearg)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>reduce (collection, iteratee, accumulator)](#apidoc.element.grunt.util._.reduce)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>reduceRight (collection, iteratee, accumulator)](#apidoc.element.grunt.util._.reduceRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>reject (collection, predicate)](#apidoc.element.grunt.util._.reject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>remove (array, predicate)](#apidoc.element.grunt.util._.remove)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>repeat (str, qty, separator)](#apidoc.element.grunt.util._.repeat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>replace ()](#apidoc.element.grunt.util._.replace)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>replaceAll (str, find, replace, ignorecase)](#apidoc.element.grunt.util._.replaceAll)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>rest (func, start)](#apidoc.element.grunt.util._.rest)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>result (object, path, defaultValue)](#apidoc.element.grunt.util._.result)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>reverse (array)](#apidoc.element.grunt.util._.reverse)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>rjust (str, length, padStr)](#apidoc.element.grunt.util._.rjust)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>round (number, precision)](#apidoc.element.grunt.util._.round)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>rpad (str, length, padStr)](#apidoc.element.grunt.util._.rpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>rstrip (str, characters)](#apidoc.element.grunt.util._.rstrip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>rtrim (str, characters)](#apidoc.element.grunt.util._.rtrim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>runInContext (context)](#apidoc.element.grunt.util._.runInContext)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sample (collection)](#apidoc.element.grunt.util._.sample)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sampleSize (collection, n)](#apidoc.element.grunt.util._.sampleSize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>set (object, path, value)](#apidoc.element.grunt.util._.set)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>setWith (object, path, value, customizer)](#apidoc.element.grunt.util._.setWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>shuffle (collection)](#apidoc.element.grunt.util._.shuffle)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>size (collection)](#apidoc.element.grunt.util._.size)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>slice (array, start, end)](#apidoc.element.grunt.util._.slice)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>slugify (str)](#apidoc.element.grunt.util._.slugify)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>snakeCase (string)](#apidoc.element.grunt.util._.snakeCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>some (collection, predicate, guard)](#apidoc.element.grunt.util._.some)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortBy ()](#apidoc.element.grunt.util._.sortBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortedIndex (array, value)](#apidoc.element.grunt.util._.sortedIndex)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortedIndexBy (array, value, iteratee)](#apidoc.element.grunt.util._.sortedIndexBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortedIndexOf (array, value)](#apidoc.element.grunt.util._.sortedIndexOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortedLastIndex (array, value)](#apidoc.element.grunt.util._.sortedLastIndex)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortedLastIndexBy (array, value, iteratee)](#apidoc.element.grunt.util._.sortedLastIndexBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortedLastIndexOf (array, value)](#apidoc.element.grunt.util._.sortedLastIndexOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortedUniq (array)](#apidoc.element.grunt.util._.sortedUniq)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sortedUniqBy (array, iteratee)](#apidoc.element.grunt.util._.sortedUniqBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>splice (str, i, howmany, substr)](#apidoc.element.grunt.util._.splice)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>split (string, separator, limit)](#apidoc.element.grunt.util._.split)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>spread (func, start)](#apidoc.element.grunt.util._.spread)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sprintf ()](#apidoc.element.grunt.util._.sprintf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>startCase (string)](#apidoc.element.grunt.util._.startCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>startsWith (str, starts, position)](#apidoc.element.grunt.util._.startsWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>str (value)](#apidoc.element.grunt.util._.str)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>strLeft (str, sep)](#apidoc.element.grunt.util._.strLeft)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>strLeftBack (str, sep)](#apidoc.element.grunt.util._.strLeftBack)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>strRight (str, sep)](#apidoc.element.grunt.util._.strRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>strRightBack (str, sep)](#apidoc.element.grunt.util._.strRightBack)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>strip (str, characters)](#apidoc.element.grunt.util._.strip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>stripTags (str)](#apidoc.element.grunt.util._.stripTags)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>subtract (minuend, subtrahend)](#apidoc.element.grunt.util._.subtract)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>succ (str)](#apidoc.element.grunt.util._.succ)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sum (array)](#apidoc.element.grunt.util._.sum)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>sumBy (array, iteratee)](#apidoc.element.grunt.util._.sumBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>surround (str, wrapper)](#apidoc.element.grunt.util._.surround)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>swapCase (str)](#apidoc.element.grunt.util._.swapCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>tail (array)](#apidoc.element.grunt.util._.tail)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>take (array, n, guard)](#apidoc.element.grunt.util._.take)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>takeRight (array, n, guard)](#apidoc.element.grunt.util._.takeRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>takeRightWhile (array, predicate)](#apidoc.element.grunt.util._.takeRightWhile)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>takeWhile (array, predicate)](#apidoc.element.grunt.util._.takeWhile)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>tap (value, interceptor)](#apidoc.element.grunt.util._.tap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>template (string, options, guard)](#apidoc.element.grunt.util._.template)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>throttle (func, wait, options)](#apidoc.element.grunt.util._.throttle)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>thru (value, interceptor)](#apidoc.element.grunt.util._.thru)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>times (n, iteratee)](#apidoc.element.grunt.util._.times)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>titleize (str)](#apidoc.element.grunt.util._.titleize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toArray (value)](#apidoc.element.grunt.util._.toArray)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toBool (str, trueValues, falseValues)](#apidoc.element.grunt.util._.toBool)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toBoolean (str, trueValues, falseValues)](#apidoc.element.grunt.util._.toBoolean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toInteger (value)](#apidoc.element.grunt.util._.toInteger)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toLength (value)](#apidoc.element.grunt.util._.toLength)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toLower (value)](#apidoc.element.grunt.util._.toLower)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toNumber (num, precision)](#apidoc.element.grunt.util._.toNumber)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toPairs (object)](#apidoc.element.grunt.util._.toPairs)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toPairsIn (object)](#apidoc.element.grunt.util._.toPairsIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toPath (value)](#apidoc.element.grunt.util._.toPath)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toPlainObject (value)](#apidoc.element.grunt.util._.toPlainObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toSafeInteger (value)](#apidoc.element.grunt.util._.toSafeInteger)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toSentence (array, separator, lastSeparator, serial)](#apidoc.element.grunt.util._.toSentence)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toSentenceSerial (array, sep, lastSep)](#apidoc.element.grunt.util._.toSentenceSerial)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toString (value)](#apidoc.element.grunt.util._.toString)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>toUpper (value)](#apidoc.element.grunt.util._.toUpper)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>transform (object, iteratee, accumulator)](#apidoc.element.grunt.util._.transform)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>trim (str, characters)](#apidoc.element.grunt.util._.trim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>trimEnd (string, chars, guard)](#apidoc.element.grunt.util._.trimEnd)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>trimStart (string, chars, guard)](#apidoc.element.grunt.util._.trimStart)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>truncate (str, length, truncateStr)](#apidoc.element.grunt.util._.truncate)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unary (func)](#apidoc.element.grunt.util._.unary)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>underscored (str)](#apidoc.element.grunt.util._.underscored)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unescape (string)](#apidoc.element.grunt.util._.unescape)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unescapeHTML (str)](#apidoc.element.grunt.util._.unescapeHTML)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>union ()](#apidoc.element.grunt.util._.union)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unionBy ()](#apidoc.element.grunt.util._.unionBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unionWith ()](#apidoc.element.grunt.util._.unionWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>uniq (array)](#apidoc.element.grunt.util._.uniq)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>uniqBy (array, iteratee)](#apidoc.element.grunt.util._.uniqBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>uniqWith (array, comparator)](#apidoc.element.grunt.util._.uniqWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>uniqueId (prefix)](#apidoc.element.grunt.util._.uniqueId)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unquote (str, quoteChar)](#apidoc.element.grunt.util._.unquote)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unset (object, path)](#apidoc.element.grunt.util._.unset)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unzip (array)](#apidoc.element.grunt.util._.unzip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>unzipWith (array, iteratee)](#apidoc.element.grunt.util._.unzipWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>upperCase (string)](#apidoc.element.grunt.util._.upperCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>upperFirst (string)](#apidoc.element.grunt.util._.upperFirst)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>values (object)](#apidoc.element.grunt.util._.values)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>valuesIn (object)](#apidoc.element.grunt.util._.valuesIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>vsprintf (fmt, argv)](#apidoc.element.grunt.util._.vsprintf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>without ()](#apidoc.element.grunt.util._.without)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>words (str, delimiter)](#apidoc.element.grunt.util._.words)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>wrap (str, options)](#apidoc.element.grunt.util._.wrap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>xor ()](#apidoc.element.grunt.util._.xor)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>xorBy ()](#apidoc.element.grunt.util._.xorBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>xorWith ()](#apidoc.element.grunt.util._.xorWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>zip ()](#apidoc.element.grunt.util._.zip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>zipObject (props, values)](#apidoc.element.grunt.util._.zipObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>zipObjectDeep (props, values)](#apidoc.element.grunt.util._.zipObjectDeep)
1.  [function <span class="apidocSignatureSpan">grunt.util._.</span>zipWith ()](#apidoc.element.grunt.util._.zipWith)
1.  object <span class="apidocSignatureSpan">grunt.util._.</span>templateSettings
1.  string <span class="apidocSignatureSpan">grunt.util._.</span>VERSION

#### [module grunt.util._.prototype](#apidoc.module.grunt.util._.prototype)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>add ()](#apidoc.element.grunt.util._.prototype.add)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>after ()](#apidoc.element.grunt.util._.prototype.after)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>ary ()](#apidoc.element.grunt.util._.prototype.ary)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>assign ()](#apidoc.element.grunt.util._.prototype.assign)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>assignIn ()](#apidoc.element.grunt.util._.prototype.assignIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>assignInWith ()](#apidoc.element.grunt.util._.prototype.assignInWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>assignWith ()](#apidoc.element.grunt.util._.prototype.assignWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>at ()](#apidoc.element.grunt.util._.prototype.at)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>attempt ()](#apidoc.element.grunt.util._.prototype.attempt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>before ()](#apidoc.element.grunt.util._.prototype.before)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>bind ()](#apidoc.element.grunt.util._.prototype.bind)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>bindAll ()](#apidoc.element.grunt.util._.prototype.bindAll)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>bindKey ()](#apidoc.element.grunt.util._.prototype.bindKey)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>camelCase ()](#apidoc.element.grunt.util._.prototype.camelCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>camelcase ()](#apidoc.element.grunt.util._.prototype.camelcase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>camelize ()](#apidoc.element.grunt.util._.prototype.camelize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>capitalize ()](#apidoc.element.grunt.util._.prototype.capitalize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>ceil ()](#apidoc.element.grunt.util._.prototype.ceil)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>center ()](#apidoc.element.grunt.util._.prototype.center)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>chain ()](#apidoc.element.grunt.util._.prototype.chain)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>chars ()](#apidoc.element.grunt.util._.prototype.chars)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>chop ()](#apidoc.element.grunt.util._.prototype.chop)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>chunk ()](#apidoc.element.grunt.util._.prototype.chunk)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>clamp ()](#apidoc.element.grunt.util._.prototype.clamp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>classify ()](#apidoc.element.grunt.util._.prototype.classify)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>clean ()](#apidoc.element.grunt.util._.prototype.clean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cleanDiacritics ()](#apidoc.element.grunt.util._.prototype.cleanDiacritics)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>clone ()](#apidoc.element.grunt.util._.prototype.clone)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cloneDeep ()](#apidoc.element.grunt.util._.prototype.cloneDeep)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cloneDeepWith ()](#apidoc.element.grunt.util._.prototype.cloneDeepWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cloneWith ()](#apidoc.element.grunt.util._.prototype.cloneWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>commit ()](#apidoc.element.grunt.util._.prototype.commit)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>compact ()](#apidoc.element.grunt.util._.prototype.compact)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>concat ()](#apidoc.element.grunt.util._.prototype.concat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cond ()](#apidoc.element.grunt.util._.prototype.cond)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>conforms ()](#apidoc.element.grunt.util._.prototype.conforms)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>constant ()](#apidoc.element.grunt.util._.prototype.constant)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>count ()](#apidoc.element.grunt.util._.prototype.count)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>countBy ()](#apidoc.element.grunt.util._.prototype.countBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>create ()](#apidoc.element.grunt.util._.prototype.create)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>curry ()](#apidoc.element.grunt.util._.prototype.curry)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>curryRight ()](#apidoc.element.grunt.util._.prototype.curryRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dasherize ()](#apidoc.element.grunt.util._.prototype.dasherize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>debounce ()](#apidoc.element.grunt.util._.prototype.debounce)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>deburr ()](#apidoc.element.grunt.util._.prototype.deburr)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>decapitalize ()](#apidoc.element.grunt.util._.prototype.decapitalize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dedent ()](#apidoc.element.grunt.util._.prototype.dedent)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>defaults ()](#apidoc.element.grunt.util._.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>defaultsDeep ()](#apidoc.element.grunt.util._.prototype.defaultsDeep)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>defer ()](#apidoc.element.grunt.util._.prototype.defer)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>delay ()](#apidoc.element.grunt.util._.prototype.delay)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>difference ()](#apidoc.element.grunt.util._.prototype.difference)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>differenceBy ()](#apidoc.element.grunt.util._.prototype.differenceBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>differenceWith ()](#apidoc.element.grunt.util._.prototype.differenceWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>drop ()](#apidoc.element.grunt.util._.prototype.drop)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dropRight ()](#apidoc.element.grunt.util._.prototype.dropRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dropRightWhile ()](#apidoc.element.grunt.util._.prototype.dropRightWhile)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dropWhile ()](#apidoc.element.grunt.util._.prototype.dropWhile)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>each ()](#apidoc.element.grunt.util._.prototype.each)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>eachRight ()](#apidoc.element.grunt.util._.prototype.eachRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>endsWith ()](#apidoc.element.grunt.util._.prototype.endsWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>eq ()](#apidoc.element.grunt.util._.prototype.eq)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>escape ()](#apidoc.element.grunt.util._.prototype.escape)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>escapeHTML ()](#apidoc.element.grunt.util._.prototype.escapeHTML)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>escapeRegExp ()](#apidoc.element.grunt.util._.prototype.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>every ()](#apidoc.element.grunt.util._.prototype.every)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>exports ()](#apidoc.element.grunt.util._.prototype.exports)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>extend ()](#apidoc.element.grunt.util._.prototype.extend)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>extendWith ()](#apidoc.element.grunt.util._.prototype.extendWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>fill ()](#apidoc.element.grunt.util._.prototype.fill)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>filter ()](#apidoc.element.grunt.util._.prototype.filter)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>find ()](#apidoc.element.grunt.util._.prototype.find)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findIndex ()](#apidoc.element.grunt.util._.prototype.findIndex)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findKey ()](#apidoc.element.grunt.util._.prototype.findKey)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findLast ()](#apidoc.element.grunt.util._.prototype.findLast)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findLastIndex ()](#apidoc.element.grunt.util._.prototype.findLastIndex)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findLastKey ()](#apidoc.element.grunt.util._.prototype.findLastKey)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>first ()](#apidoc.element.grunt.util._.prototype.first)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flatMap (iteratee)](#apidoc.element.grunt.util._.prototype.flatMap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flatten ()](#apidoc.element.grunt.util._.prototype.flatten)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flattenDeep ()](#apidoc.element.grunt.util._.prototype.flattenDeep)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flip ()](#apidoc.element.grunt.util._.prototype.flip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>floor ()](#apidoc.element.grunt.util._.prototype.floor)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flow ()](#apidoc.element.grunt.util._.prototype.flow)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flowRight ()](#apidoc.element.grunt.util._.prototype.flowRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forEach ()](#apidoc.element.grunt.util._.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forEachRight ()](#apidoc.element.grunt.util._.prototype.forEachRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forIn ()](#apidoc.element.grunt.util._.prototype.forIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forInRight ()](#apidoc.element.grunt.util._.prototype.forInRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forOwn ()](#apidoc.element.grunt.util._.prototype.forOwn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forOwnRight ()](#apidoc.element.grunt.util._.prototype.forOwnRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>fromPairs ()](#apidoc.element.grunt.util._.prototype.fromPairs)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>functions ()](#apidoc.element.grunt.util._.prototype.functions)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>functionsIn ()](#apidoc.element.grunt.util._.prototype.functionsIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>get ()](#apidoc.element.grunt.util._.prototype.get)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>groupBy ()](#apidoc.element.grunt.util._.prototype.groupBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>gt ()](#apidoc.element.grunt.util._.prototype.gt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>gte ()](#apidoc.element.grunt.util._.prototype.gte)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>has ()](#apidoc.element.grunt.util._.prototype.has)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>hasIn ()](#apidoc.element.grunt.util._.prototype.hasIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>head ()](#apidoc.element.grunt.util._.prototype.head)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>humanize ()](#apidoc.element.grunt.util._.prototype.humanize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>identity ()](#apidoc.element.grunt.util._.prototype.identity)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>inRange ()](#apidoc.element.grunt.util._.prototype.inRange)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>includes ()](#apidoc.element.grunt.util._.prototype.includes)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>indexOf ()](#apidoc.element.grunt.util._.prototype.indexOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>initial ()](#apidoc.element.grunt.util._.prototype.initial)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>insert ()](#apidoc.element.grunt.util._.prototype.insert)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>intersection ()](#apidoc.element.grunt.util._.prototype.intersection)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>intersectionBy ()](#apidoc.element.grunt.util._.prototype.intersectionBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>intersectionWith ()](#apidoc.element.grunt.util._.prototype.intersectionWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>invert ()](#apidoc.element.grunt.util._.prototype.invert)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>invertBy ()](#apidoc.element.grunt.util._.prototype.invertBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>invoke ()](#apidoc.element.grunt.util._.prototype.invoke)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>invokeMap ()](#apidoc.element.grunt.util._.prototype.invokeMap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArguments ()](#apidoc.element.grunt.util._.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArray ()](#apidoc.element.grunt.util._.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArrayBuffer ()](#apidoc.element.grunt.util._.prototype.isArrayBuffer)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArrayLike ()](#apidoc.element.grunt.util._.prototype.isArrayLike)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArrayLikeObject ()](#apidoc.element.grunt.util._.prototype.isArrayLikeObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isBlank ()](#apidoc.element.grunt.util._.prototype.isBlank)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isBoolean ()](#apidoc.element.grunt.util._.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isBuffer ()](#apidoc.element.grunt.util._.prototype.isBuffer)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isDate ()](#apidoc.element.grunt.util._.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isElement ()](#apidoc.element.grunt.util._.prototype.isElement)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isEmpty ()](#apidoc.element.grunt.util._.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isEqual ()](#apidoc.element.grunt.util._.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isEqualWith ()](#apidoc.element.grunt.util._.prototype.isEqualWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isError ()](#apidoc.element.grunt.util._.prototype.isError)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isFinite ()](#apidoc.element.grunt.util._.prototype.isFinite)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isFunction ()](#apidoc.element.grunt.util._.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isInteger ()](#apidoc.element.grunt.util._.prototype.isInteger)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isLength ()](#apidoc.element.grunt.util._.prototype.isLength)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isMap ()](#apidoc.element.grunt.util._.prototype.isMap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isMatch ()](#apidoc.element.grunt.util._.prototype.isMatch)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isMatchWith ()](#apidoc.element.grunt.util._.prototype.isMatchWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNaN ()](#apidoc.element.grunt.util._.prototype.isNaN)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNative ()](#apidoc.element.grunt.util._.prototype.isNative)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNil ()](#apidoc.element.grunt.util._.prototype.isNil)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNull ()](#apidoc.element.grunt.util._.prototype.isNull)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNumber ()](#apidoc.element.grunt.util._.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isObject ()](#apidoc.element.grunt.util._.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isObjectLike ()](#apidoc.element.grunt.util._.prototype.isObjectLike)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isPlainObject ()](#apidoc.element.grunt.util._.prototype.isPlainObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isRegExp ()](#apidoc.element.grunt.util._.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isSafeInteger ()](#apidoc.element.grunt.util._.prototype.isSafeInteger)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isSet ()](#apidoc.element.grunt.util._.prototype.isSet)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isString ()](#apidoc.element.grunt.util._.prototype.isString)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isSymbol ()](#apidoc.element.grunt.util._.prototype.isSymbol)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isTypedArray ()](#apidoc.element.grunt.util._.prototype.isTypedArray)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isUndefined ()](#apidoc.element.grunt.util._.prototype.isUndefined)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isWeakMap ()](#apidoc.element.grunt.util._.prototype.isWeakMap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isWeakSet ()](#apidoc.element.grunt.util._.prototype.isWeakSet)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>iteratee ()](#apidoc.element.grunt.util._.prototype.iteratee)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>join ()](#apidoc.element.grunt.util._.prototype.join)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>kebabCase ()](#apidoc.element.grunt.util._.prototype.kebabCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>keyBy ()](#apidoc.element.grunt.util._.prototype.keyBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>keys ()](#apidoc.element.grunt.util._.prototype.keys)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>keysIn ()](#apidoc.element.grunt.util._.prototype.keysIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>last ()](#apidoc.element.grunt.util._.prototype.last)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lastIndexOf ()](#apidoc.element.grunt.util._.prototype.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>levenshtein ()](#apidoc.element.grunt.util._.prototype.levenshtein)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lines ()](#apidoc.element.grunt.util._.prototype.lines)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>ljust ()](#apidoc.element.grunt.util._.prototype.ljust)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lowerCase ()](#apidoc.element.grunt.util._.prototype.lowerCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lowerFirst ()](#apidoc.element.grunt.util._.prototype.lowerFirst)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lpad ()](#apidoc.element.grunt.util._.prototype.lpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lrpad ()](#apidoc.element.grunt.util._.prototype.lrpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lstrip ()](#apidoc.element.grunt.util._.prototype.lstrip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lt ()](#apidoc.element.grunt.util._.prototype.lt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lte ()](#apidoc.element.grunt.util._.prototype.lte)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>ltrim ()](#apidoc.element.grunt.util._.prototype.ltrim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>map ()](#apidoc.element.grunt.util._.prototype.map)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mapChars ()](#apidoc.element.grunt.util._.prototype.mapChars)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mapKeys ()](#apidoc.element.grunt.util._.prototype.mapKeys)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mapValues ()](#apidoc.element.grunt.util._.prototype.mapValues)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>matches ()](#apidoc.element.grunt.util._.prototype.matches)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>matchesProperty ()](#apidoc.element.grunt.util._.prototype.matchesProperty)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>max ()](#apidoc.element.grunt.util._.prototype.max)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>maxBy ()](#apidoc.element.grunt.util._.prototype.maxBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mean ()](#apidoc.element.grunt.util._.prototype.mean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>memoize ()](#apidoc.element.grunt.util._.prototype.memoize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>merge ()](#apidoc.element.grunt.util._.prototype.merge)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mergeWith ()](#apidoc.element.grunt.util._.prototype.mergeWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>method ()](#apidoc.element.grunt.util._.prototype.method)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>methodOf ()](#apidoc.element.grunt.util._.prototype.methodOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>min ()](#apidoc.element.grunt.util._.prototype.min)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>minBy ()](#apidoc.element.grunt.util._.prototype.minBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mixin ()](#apidoc.element.grunt.util._.prototype.mixin)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>naturalCmp ()](#apidoc.element.grunt.util._.prototype.naturalCmp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>negate ()](#apidoc.element.grunt.util._.prototype.negate)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>next ()](#apidoc.element.grunt.util._.prototype.next)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>noConflict ()](#apidoc.element.grunt.util._.prototype.noConflict)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>noop ()](#apidoc.element.grunt.util._.prototype.noop)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>now ()](#apidoc.element.grunt.util._.prototype.now)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>nthArg ()](#apidoc.element.grunt.util._.prototype.nthArg)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>numberFormat ()](#apidoc.element.grunt.util._.prototype.numberFormat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>omit ()](#apidoc.element.grunt.util._.prototype.omit)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>omitBy ()](#apidoc.element.grunt.util._.prototype.omitBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>once ()](#apidoc.element.grunt.util._.prototype.once)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>orderBy ()](#apidoc.element.grunt.util._.prototype.orderBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>over ()](#apidoc.element.grunt.util._.prototype.over)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>overArgs ()](#apidoc.element.grunt.util._.prototype.overArgs)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>overEvery ()](#apidoc.element.grunt.util._.prototype.overEvery)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>overSome ()](#apidoc.element.grunt.util._.prototype.overSome)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pad ()](#apidoc.element.grunt.util._.prototype.pad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>padEnd ()](#apidoc.element.grunt.util._.prototype.padEnd)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>padStart ()](#apidoc.element.grunt.util._.prototype.padStart)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>parseInt ()](#apidoc.element.grunt.util._.prototype.parseInt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>partial ()](#apidoc.element.grunt.util._.prototype.partial)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>partialRight ()](#apidoc.element.grunt.util._.prototype.partialRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>partition ()](#apidoc.element.grunt.util._.prototype.partition)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pick ()](#apidoc.element.grunt.util._.prototype.pick)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pickBy ()](#apidoc.element.grunt.util._.prototype.pickBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>plant (value)](#apidoc.element.grunt.util._.prototype.plant)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pop ()](#apidoc.element.grunt.util._.prototype.pop)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pred ()](#apidoc.element.grunt.util._.prototype.pred)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>property ()](#apidoc.element.grunt.util._.prototype.property)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>propertyOf ()](#apidoc.element.grunt.util._.prototype.propertyOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>prune ()](#apidoc.element.grunt.util._.prototype.prune)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pull ()](#apidoc.element.grunt.util._.prototype.pull)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pullAll ()](#apidoc.element.grunt.util._.prototype.pullAll)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pullAllBy ()](#apidoc.element.grunt.util._.prototype.pullAllBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pullAt ()](#apidoc.element.grunt.util._.prototype.pullAt)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>push ()](#apidoc.element.grunt.util._.prototype.push)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>q ()](#apidoc.element.grunt.util._.prototype.q)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>quote ()](#apidoc.element.grunt.util._.prototype.quote)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>random ()](#apidoc.element.grunt.util._.prototype.random)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>range ()](#apidoc.element.grunt.util._.prototype.range)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rangeRight ()](#apidoc.element.grunt.util._.prototype.rangeRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rearg ()](#apidoc.element.grunt.util._.prototype.rearg)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>reduce ()](#apidoc.element.grunt.util._.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>reduceRight ()](#apidoc.element.grunt.util._.prototype.reduceRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>reject ()](#apidoc.element.grunt.util._.prototype.reject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>remove ()](#apidoc.element.grunt.util._.prototype.remove)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>repeat ()](#apidoc.element.grunt.util._.prototype.repeat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>replace ()](#apidoc.element.grunt.util._.prototype.replace)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>replaceAll ()](#apidoc.element.grunt.util._.prototype.replaceAll)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rest ()](#apidoc.element.grunt.util._.prototype.rest)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>result ()](#apidoc.element.grunt.util._.prototype.result)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>reverse ()](#apidoc.element.grunt.util._.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rjust ()](#apidoc.element.grunt.util._.prototype.rjust)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>round ()](#apidoc.element.grunt.util._.prototype.round)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rpad ()](#apidoc.element.grunt.util._.prototype.rpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rstrip ()](#apidoc.element.grunt.util._.prototype.rstrip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rtrim ()](#apidoc.element.grunt.util._.prototype.rtrim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>runInContext ()](#apidoc.element.grunt.util._.prototype.runInContext)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sample ()](#apidoc.element.grunt.util._.prototype.sample)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sampleSize ()](#apidoc.element.grunt.util._.prototype.sampleSize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>set ()](#apidoc.element.grunt.util._.prototype.set)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>setWith ()](#apidoc.element.grunt.util._.prototype.setWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>shift ()](#apidoc.element.grunt.util._.prototype.shift)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>shuffle ()](#apidoc.element.grunt.util._.prototype.shuffle)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>size ()](#apidoc.element.grunt.util._.prototype.size)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>slice ()](#apidoc.element.grunt.util._.prototype.slice)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>slugify ()](#apidoc.element.grunt.util._.prototype.slugify)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>snakeCase ()](#apidoc.element.grunt.util._.prototype.snakeCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>some ()](#apidoc.element.grunt.util._.prototype.some)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sort ()](#apidoc.element.grunt.util._.prototype.sort)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortBy ()](#apidoc.element.grunt.util._.prototype.sortBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedIndex ()](#apidoc.element.grunt.util._.prototype.sortedIndex)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedIndexBy ()](#apidoc.element.grunt.util._.prototype.sortedIndexBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedIndexOf ()](#apidoc.element.grunt.util._.prototype.sortedIndexOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedLastIndex ()](#apidoc.element.grunt.util._.prototype.sortedLastIndex)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedLastIndexBy ()](#apidoc.element.grunt.util._.prototype.sortedLastIndexBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedLastIndexOf ()](#apidoc.element.grunt.util._.prototype.sortedLastIndexOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedUniq ()](#apidoc.element.grunt.util._.prototype.sortedUniq)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedUniqBy ()](#apidoc.element.grunt.util._.prototype.sortedUniqBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>splice ()](#apidoc.element.grunt.util._.prototype.splice)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>split ()](#apidoc.element.grunt.util._.prototype.split)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>spread ()](#apidoc.element.grunt.util._.prototype.spread)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sprintf ()](#apidoc.element.grunt.util._.prototype.sprintf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>startCase ()](#apidoc.element.grunt.util._.prototype.startCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>startsWith ()](#apidoc.element.grunt.util._.prototype.startsWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strLeft ()](#apidoc.element.grunt.util._.prototype.strLeft)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strLeftBack ()](#apidoc.element.grunt.util._.prototype.strLeftBack)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strRight ()](#apidoc.element.grunt.util._.prototype.strRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strRightBack ()](#apidoc.element.grunt.util._.prototype.strRightBack)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strip ()](#apidoc.element.grunt.util._.prototype.strip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>stripTags ()](#apidoc.element.grunt.util._.prototype.stripTags)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>subtract ()](#apidoc.element.grunt.util._.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>succ ()](#apidoc.element.grunt.util._.prototype.succ)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sum ()](#apidoc.element.grunt.util._.prototype.sum)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sumBy ()](#apidoc.element.grunt.util._.prototype.sumBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>surround ()](#apidoc.element.grunt.util._.prototype.surround)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>swapCase ()](#apidoc.element.grunt.util._.prototype.swapCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>tail ()](#apidoc.element.grunt.util._.prototype.tail)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>take ()](#apidoc.element.grunt.util._.prototype.take)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>takeRight ()](#apidoc.element.grunt.util._.prototype.takeRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>takeRightWhile ()](#apidoc.element.grunt.util._.prototype.takeRightWhile)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>takeWhile ()](#apidoc.element.grunt.util._.prototype.takeWhile)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>tap ()](#apidoc.element.grunt.util._.prototype.tap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>template ()](#apidoc.element.grunt.util._.prototype.template)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>throttle ()](#apidoc.element.grunt.util._.prototype.throttle)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>thru ()](#apidoc.element.grunt.util._.prototype.thru)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>times ()](#apidoc.element.grunt.util._.prototype.times)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>titleize ()](#apidoc.element.grunt.util._.prototype.titleize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toArray ()](#apidoc.element.grunt.util._.prototype.toArray)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toBool ()](#apidoc.element.grunt.util._.prototype.toBool)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toBoolean ()](#apidoc.element.grunt.util._.prototype.toBoolean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toInteger ()](#apidoc.element.grunt.util._.prototype.toInteger)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toJSON ()](#apidoc.element.grunt.util._.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toLength ()](#apidoc.element.grunt.util._.prototype.toLength)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toLower ()](#apidoc.element.grunt.util._.prototype.toLower)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toNumber ()](#apidoc.element.grunt.util._.prototype.toNumber)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toPairs ()](#apidoc.element.grunt.util._.prototype.toPairs)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toPairsIn ()](#apidoc.element.grunt.util._.prototype.toPairsIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toPath ()](#apidoc.element.grunt.util._.prototype.toPath)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toPlainObject ()](#apidoc.element.grunt.util._.prototype.toPlainObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toSafeInteger ()](#apidoc.element.grunt.util._.prototype.toSafeInteger)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toSentence ()](#apidoc.element.grunt.util._.prototype.toSentence)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toSentenceSerial ()](#apidoc.element.grunt.util._.prototype.toSentenceSerial)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toString ()](#apidoc.element.grunt.util._.prototype.toString)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toUpper ()](#apidoc.element.grunt.util._.prototype.toUpper)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>transform ()](#apidoc.element.grunt.util._.prototype.transform)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>trim ()](#apidoc.element.grunt.util._.prototype.trim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>trimEnd ()](#apidoc.element.grunt.util._.prototype.trimEnd)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>trimStart ()](#apidoc.element.grunt.util._.prototype.trimStart)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>truncate ()](#apidoc.element.grunt.util._.prototype.truncate)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unary ()](#apidoc.element.grunt.util._.prototype.unary)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>underscored ()](#apidoc.element.grunt.util._.prototype.underscored)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unescape ()](#apidoc.element.grunt.util._.prototype.unescape)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unescapeHTML ()](#apidoc.element.grunt.util._.prototype.unescapeHTML)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>union ()](#apidoc.element.grunt.util._.prototype.union)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unionBy ()](#apidoc.element.grunt.util._.prototype.unionBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unionWith ()](#apidoc.element.grunt.util._.prototype.unionWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>uniq ()](#apidoc.element.grunt.util._.prototype.uniq)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>uniqBy ()](#apidoc.element.grunt.util._.prototype.uniqBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>uniqWith ()](#apidoc.element.grunt.util._.prototype.uniqWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>uniqueId ()](#apidoc.element.grunt.util._.prototype.uniqueId)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unquote ()](#apidoc.element.grunt.util._.prototype.unquote)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unset ()](#apidoc.element.grunt.util._.prototype.unset)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unshift ()](#apidoc.element.grunt.util._.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unzip ()](#apidoc.element.grunt.util._.prototype.unzip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unzipWith ()](#apidoc.element.grunt.util._.prototype.unzipWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>upperCase ()](#apidoc.element.grunt.util._.prototype.upperCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>upperFirst ()](#apidoc.element.grunt.util._.prototype.upperFirst)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>value ()](#apidoc.element.grunt.util._.prototype.value)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>valueOf ()](#apidoc.element.grunt.util._.prototype.valueOf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>values ()](#apidoc.element.grunt.util._.prototype.values)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>valuesIn ()](#apidoc.element.grunt.util._.prototype.valuesIn)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>vsprintf ()](#apidoc.element.grunt.util._.prototype.vsprintf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>without ()](#apidoc.element.grunt.util._.prototype.without)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>words ()](#apidoc.element.grunt.util._.prototype.words)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>wrap ()](#apidoc.element.grunt.util._.prototype.wrap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>xor ()](#apidoc.element.grunt.util._.prototype.xor)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>xorBy ()](#apidoc.element.grunt.util._.prototype.xorBy)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>xorWith ()](#apidoc.element.grunt.util._.prototype.xorWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>zip ()](#apidoc.element.grunt.util._.prototype.zip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>zipObject ()](#apidoc.element.grunt.util._.prototype.zipObject)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>zipObjectDeep ()](#apidoc.element.grunt.util._.prototype.zipObjectDeep)
1.  [function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>zipWith ()](#apidoc.element.grunt.util._.prototype.zipWith)

#### [module grunt.util._.str.prototype](#apidoc.module.grunt.util._.str.prototype)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>camelcase ()](#apidoc.element.grunt.util._.str.prototype.camelcase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>camelize ()](#apidoc.element.grunt.util._.str.prototype.camelize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>capitalize ()](#apidoc.element.grunt.util._.str.prototype.capitalize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>center ()](#apidoc.element.grunt.util._.str.prototype.center)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>chars ()](#apidoc.element.grunt.util._.str.prototype.chars)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>chop ()](#apidoc.element.grunt.util._.str.prototype.chop)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>classify ()](#apidoc.element.grunt.util._.str.prototype.classify)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>clean ()](#apidoc.element.grunt.util._.str.prototype.clean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>cleanDiacritics ()](#apidoc.element.grunt.util._.str.prototype.cleanDiacritics)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>concat ()](#apidoc.element.grunt.util._.str.prototype.concat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>contains ()](#apidoc.element.grunt.util._.str.prototype.contains)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>count ()](#apidoc.element.grunt.util._.str.prototype.count)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>dasherize ()](#apidoc.element.grunt.util._.str.prototype.dasherize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>decapitalize ()](#apidoc.element.grunt.util._.str.prototype.decapitalize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>dedent ()](#apidoc.element.grunt.util._.str.prototype.dedent)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>endsWith ()](#apidoc.element.grunt.util._.str.prototype.endsWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>escapeHTML ()](#apidoc.element.grunt.util._.str.prototype.escapeHTML)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>escapeRegExp ()](#apidoc.element.grunt.util._.str.prototype.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>exports ()](#apidoc.element.grunt.util._.str.prototype.exports)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>humanize ()](#apidoc.element.grunt.util._.str.prototype.humanize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>include ()](#apidoc.element.grunt.util._.str.prototype.include)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>insert ()](#apidoc.element.grunt.util._.str.prototype.insert)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>isBlank ()](#apidoc.element.grunt.util._.str.prototype.isBlank)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>join ()](#apidoc.element.grunt.util._.str.prototype.join)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>levenshtein ()](#apidoc.element.grunt.util._.str.prototype.levenshtein)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>lines ()](#apidoc.element.grunt.util._.str.prototype.lines)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>ljust ()](#apidoc.element.grunt.util._.str.prototype.ljust)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>lpad ()](#apidoc.element.grunt.util._.str.prototype.lpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>lrpad ()](#apidoc.element.grunt.util._.str.prototype.lrpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>lstrip ()](#apidoc.element.grunt.util._.str.prototype.lstrip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>ltrim ()](#apidoc.element.grunt.util._.str.prototype.ltrim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>map ()](#apidoc.element.grunt.util._.str.prototype.map)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>mapChars ()](#apidoc.element.grunt.util._.str.prototype.mapChars)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>naturalCmp ()](#apidoc.element.grunt.util._.str.prototype.naturalCmp)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>numberFormat ()](#apidoc.element.grunt.util._.str.prototype.numberFormat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>pad ()](#apidoc.element.grunt.util._.str.prototype.pad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>pred ()](#apidoc.element.grunt.util._.str.prototype.pred)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>prune ()](#apidoc.element.grunt.util._.str.prototype.prune)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>q ()](#apidoc.element.grunt.util._.str.prototype.q)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>quote ()](#apidoc.element.grunt.util._.str.prototype.quote)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>repeat ()](#apidoc.element.grunt.util._.str.prototype.repeat)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>replace ()](#apidoc.element.grunt.util._.str.prototype.replace)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>replaceAll ()](#apidoc.element.grunt.util._.str.prototype.replaceAll)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>reverse ()](#apidoc.element.grunt.util._.str.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>rjust ()](#apidoc.element.grunt.util._.str.prototype.rjust)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>rpad ()](#apidoc.element.grunt.util._.str.prototype.rpad)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>rstrip ()](#apidoc.element.grunt.util._.str.prototype.rstrip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>rtrim ()](#apidoc.element.grunt.util._.str.prototype.rtrim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>slice ()](#apidoc.element.grunt.util._.str.prototype.slice)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>slugify ()](#apidoc.element.grunt.util._.str.prototype.slugify)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>splice ()](#apidoc.element.grunt.util._.str.prototype.splice)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>split ()](#apidoc.element.grunt.util._.str.prototype.split)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>sprintf ()](#apidoc.element.grunt.util._.str.prototype.sprintf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>startsWith ()](#apidoc.element.grunt.util._.str.prototype.startsWith)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strLeft ()](#apidoc.element.grunt.util._.str.prototype.strLeft)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strLeftBack ()](#apidoc.element.grunt.util._.str.prototype.strLeftBack)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strRight ()](#apidoc.element.grunt.util._.str.prototype.strRight)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strRightBack ()](#apidoc.element.grunt.util._.str.prototype.strRightBack)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strip ()](#apidoc.element.grunt.util._.str.prototype.strip)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>stripTags ()](#apidoc.element.grunt.util._.str.prototype.stripTags)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>substr ()](#apidoc.element.grunt.util._.str.prototype.substr)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>substring ()](#apidoc.element.grunt.util._.str.prototype.substring)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>succ ()](#apidoc.element.grunt.util._.str.prototype.succ)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>surround ()](#apidoc.element.grunt.util._.str.prototype.surround)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>swapCase ()](#apidoc.element.grunt.util._.str.prototype.swapCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>tap ()](#apidoc.element.grunt.util._.str.prototype.tap)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>titleize ()](#apidoc.element.grunt.util._.str.prototype.titleize)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toBool ()](#apidoc.element.grunt.util._.str.prototype.toBool)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toBoolean ()](#apidoc.element.grunt.util._.str.prototype.toBoolean)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toLowerCase ()](#apidoc.element.grunt.util._.str.prototype.toLowerCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toNumber ()](#apidoc.element.grunt.util._.str.prototype.toNumber)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toSentence ()](#apidoc.element.grunt.util._.str.prototype.toSentence)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toSentenceSerial ()](#apidoc.element.grunt.util._.str.prototype.toSentenceSerial)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toUpperCase ()](#apidoc.element.grunt.util._.str.prototype.toUpperCase)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>trim ()](#apidoc.element.grunt.util._.str.prototype.trim)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>truncate ()](#apidoc.element.grunt.util._.str.prototype.truncate)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>underscored ()](#apidoc.element.grunt.util._.str.prototype.underscored)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>unescapeHTML ()](#apidoc.element.grunt.util._.str.prototype.unescapeHTML)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>unquote ()](#apidoc.element.grunt.util._.str.prototype.unquote)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>value ()](#apidoc.element.grunt.util._.str.prototype.value)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>vsprintf ()](#apidoc.element.grunt.util._.str.prototype.vsprintf)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>words ()](#apidoc.element.grunt.util._.str.prototype.words)
1.  [function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>wrap ()](#apidoc.element.grunt.util._.str.prototype.wrap)

#### [module grunt.util.async](#apidoc.module.grunt.util.async)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>all (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.all)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>any (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.any)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>apply ()](#apidoc.element.grunt.util.async.apply)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>applyEach ()](#apidoc.element.grunt.util.async.applyEach)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>applyEachSeries ()](#apidoc.element.grunt.util.async.applyEachSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>asyncify (func)](#apidoc.element.grunt.util.async.asyncify)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>auto (tasks, concurrency, callback)](#apidoc.element.grunt.util.async.auto)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>cargo (worker, payload)](#apidoc.element.grunt.util.async.cargo)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>compose ()](#apidoc.element.grunt.util.async.compose)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>concat (obj, iterator, callback)](#apidoc.element.grunt.util.async.concat)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>concatSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.concatSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>constant ()](#apidoc.element.grunt.util.async.constant)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>detect (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.detect)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>detectLimit (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.detectLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>detectSeries (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.detectSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>dir ()](#apidoc.element.grunt.util.async.dir)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>doDuring (iterator, test, callback)](#apidoc.element.grunt.util.async.doDuring)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>doUntil (iterator, test, callback)](#apidoc.element.grunt.util.async.doUntil)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>doWhilst (iterator, test, callback)](#apidoc.element.grunt.util.async.doWhilst)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>during (test, iterator, callback)](#apidoc.element.grunt.util.async.during)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>each (arr, iterator, callback)](#apidoc.element.grunt.util.async.each)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>eachLimit (arr, limit, iterator, callback)](#apidoc.element.grunt.util.async.eachLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>eachOf (object, iterator, callback)](#apidoc.element.grunt.util.async.eachOf)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>eachOfLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.eachOfLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>eachOfSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.eachOfSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>eachSeries (arr, iterator, callback)](#apidoc.element.grunt.util.async.eachSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>ensureAsync (fn)](#apidoc.element.grunt.util.async.ensureAsync)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>every (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.every)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>everyLimit (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.everyLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>filter (obj, iterator, callback)](#apidoc.element.grunt.util.async.filter)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>filterLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.filterLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>filterSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.filterSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>foldl (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.foldl)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>foldr (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.foldr)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>forEach (arr, iterator, callback)](#apidoc.element.grunt.util.async.forEach)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachLimit (arr, limit, iterator, callback)](#apidoc.element.grunt.util.async.forEachLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachOf (object, iterator, callback)](#apidoc.element.grunt.util.async.forEachOf)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachOfLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.forEachOfLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachOfSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.forEachOfSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachSeries (arr, iterator, callback)](#apidoc.element.grunt.util.async.forEachSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>forever (fn, callback)](#apidoc.element.grunt.util.async.forever)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>inject (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.inject)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>iterator (tasks)](#apidoc.element.grunt.util.async.iterator)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>log ()](#apidoc.element.grunt.util.async.log)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>map (obj, iterator, callback)](#apidoc.element.grunt.util.async.map)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>mapLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.mapLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>mapSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.mapSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>memoize (fn, hasher)](#apidoc.element.grunt.util.async.memoize)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>nextTick (callback)](#apidoc.element.grunt.util.async.nextTick)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>noConflict ()](#apidoc.element.grunt.util.async.noConflict)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>parallel (tasks, callback)](#apidoc.element.grunt.util.async.parallel)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>parallelLimit (tasks, limit, callback)](#apidoc.element.grunt.util.async.parallelLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>priorityQueue (worker, concurrency)](#apidoc.element.grunt.util.async.priorityQueue)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>queue (worker, concurrency)](#apidoc.element.grunt.util.async.queue)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>reduce (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.reduce)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>reduceRight (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.reduceRight)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>reject (obj, iterator, callback)](#apidoc.element.grunt.util.async.reject)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>rejectLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.rejectLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>rejectSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.rejectSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>retry (times, task, callback)](#apidoc.element.grunt.util.async.retry)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>select (obj, iterator, callback)](#apidoc.element.grunt.util.async.select)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>selectLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.selectLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>selectSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.selectSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>seq ()](#apidoc.element.grunt.util.async.seq)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>series (tasks, callback)](#apidoc.element.grunt.util.async.series)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>setImmediate (fn)](#apidoc.element.grunt.util.async.setImmediate)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>some (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.some)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>someLimit (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.someLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>sortBy (arr, iterator, callback)](#apidoc.element.grunt.util.async.sortBy)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>times (count, iterator, callback)](#apidoc.element.grunt.util.async.times)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>timesLimit (count, limit, iterator, callback)](#apidoc.element.grunt.util.async.timesLimit)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>timesSeries (count, iterator, callback)](#apidoc.element.grunt.util.async.timesSeries)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>transform (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.transform)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>unmemoize (fn)](#apidoc.element.grunt.util.async.unmemoize)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>until (test, iterator, callback)](#apidoc.element.grunt.util.async.until)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>waterfall (tasks, callback)](#apidoc.element.grunt.util.async.waterfall)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>whilst (test, iterator, callback)](#apidoc.element.grunt.util.async.whilst)
1.  [function <span class="apidocSignatureSpan">grunt.util.async.</span>wrapSync (func)](#apidoc.element.grunt.util.async.wrapSync)

#### [module grunt.util.hooker](#apidoc.module.grunt.util.hooker)
1.  [function <span class="apidocSignatureSpan">grunt.util.hooker.</span>filter (context, args)](#apidoc.element.grunt.util.hooker.filter)
1.  [function <span class="apidocSignatureSpan">grunt.util.hooker.</span>hook (obj, props, options)](#apidoc.element.grunt.util.hooker.hook)
1.  [function <span class="apidocSignatureSpan">grunt.util.hooker.</span>orig (obj, prop)](#apidoc.element.grunt.util.hooker.orig)
1.  [function <span class="apidocSignatureSpan">grunt.util.hooker.</span>override (value)](#apidoc.element.grunt.util.hooker.override)
1.  [function <span class="apidocSignatureSpan">grunt.util.hooker.</span>preempt (value)](#apidoc.element.grunt.util.hooker.preempt)
1.  [function <span class="apidocSignatureSpan">grunt.util.hooker.</span>unhook (obj, props)](#apidoc.element.grunt.util.hooker.unhook)

#### [module grunt.util.namespace](#apidoc.module.grunt.util.namespace)
1.  [function <span class="apidocSignatureSpan">grunt.util.namespace.</span>exists (obj, parts)](#apidoc.element.grunt.util.namespace.exists)
1.  [function <span class="apidocSignatureSpan">grunt.util.namespace.</span>get (obj, parts, create)](#apidoc.element.grunt.util.namespace.get)
1.  [function <span class="apidocSignatureSpan">grunt.util.namespace.</span>set (obj, parts, value)](#apidoc.element.grunt.util.namespace.set)

#### [module grunt.util.task](#apidoc.module.grunt.util.task)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.</span>Task ()](#apidoc.element.grunt.util.task.Task)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.</span>create ()](#apidoc.element.grunt.util.task.create)

#### [module grunt.util.task.Task.prototype](#apidoc.module.grunt.util.task.Task.prototype)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>_push (things)](#apidoc.element.grunt.util.task.Task.prototype._push)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>_taskPlusArgs (name)](#apidoc.element.grunt.util.task.Task.prototype._taskPlusArgs)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>_throwIfRunning (obj)](#apidoc.element.grunt.util.task.Task.prototype._throwIfRunning)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>clearQueue (options)](#apidoc.element.grunt.util.task.Task.prototype.clearQueue)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>exists (name)](#apidoc.element.grunt.util.task.Task.prototype.exists)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>isTaskAlias (name)](#apidoc.element.grunt.util.task.Task.prototype.isTaskAlias)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>mark ()](#apidoc.element.grunt.util.task.Task.prototype.mark)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>options (options)](#apidoc.element.grunt.util.task.Task.prototype.options)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>parseArgs (args)](#apidoc.element.grunt.util.task.Task.prototype.parseArgs)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>registerTask (name, info, fn)](#apidoc.element.grunt.util.task.Task.prototype.registerTask)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>renameTask (oldname, newname)](#apidoc.element.grunt.util.task.Task.prototype.renameTask)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>requires ()](#apidoc.element.grunt.util.task.Task.prototype.requires)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>run ()](#apidoc.element.grunt.util.task.Task.prototype.run)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>runTaskFn (context, fn, done, asyncDone)](#apidoc.element.grunt.util.task.Task.prototype.runTaskFn)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>splitArgs (str)](#apidoc.element.grunt.util.task.Task.prototype.splitArgs)
1.  [function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>start (opts)](#apidoc.element.grunt.util.task.Task.prototype.start)

#### [module grunt.verbose](#apidoc.module.grunt.verbose)
1.  boolean <span class="apidocSignatureSpan">grunt.verbose.</span>_isVerbose
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>_format ()](#apidoc.element.grunt.verbose._format)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>_markup ()](#apidoc.element.grunt.verbose._markup)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>_write ()](#apidoc.element.grunt.verbose._write)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>_writeln ()](#apidoc.element.grunt.verbose._writeln)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>debug ()](#apidoc.element.grunt.verbose.debug)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>error ()](#apidoc.element.grunt.verbose.error)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>errorlns ()](#apidoc.element.grunt.verbose.errorlns)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>fail ()](#apidoc.element.grunt.verbose.fail)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>header ()](#apidoc.element.grunt.verbose.header)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>initColors ()](#apidoc.element.grunt.verbose.initColors)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>ok ()](#apidoc.element.grunt.verbose.ok)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>oklns ()](#apidoc.element.grunt.verbose.oklns)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>option ()](#apidoc.element.grunt.verbose.option)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>subhead ()](#apidoc.element.grunt.verbose.subhead)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>success ()](#apidoc.element.grunt.verbose.success)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>table ()](#apidoc.element.grunt.verbose.table)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>uncolor ()](#apidoc.element.grunt.verbose.uncolor)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>warn ()](#apidoc.element.grunt.verbose.warn)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>wordlist ()](#apidoc.element.grunt.verbose.wordlist)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>wraptext ()](#apidoc.element.grunt.verbose.wraptext)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>write ()](#apidoc.element.grunt.verbose.write)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>writeflags ()](#apidoc.element.grunt.verbose.writeflags)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>writeln ()](#apidoc.element.grunt.verbose.writeln)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>writelns ()](#apidoc.element.grunt.verbose.writelns)
1.  [function <span class="apidocSignatureSpan">grunt.verbose.</span>writetableln ()](#apidoc.element.grunt.verbose.writetableln)
1.  object <span class="apidocSignatureSpan">grunt.verbose.</span>always
1.  object <span class="apidocSignatureSpan">grunt.verbose.</span>or



# <a name="apidoc.module.grunt"></a>[module grunt](#apidoc.module.grunt)

#### <a name="apidoc.element.grunt.cli"></a>[function <span class="apidocSignatureSpan">grunt.</span>cli (options, done)](#apidoc.element.grunt.cli)
- description and source-code
```javascript
cli = function (options, done) {
  // CLI-parsed options override any passed-in "default" options.
  if (options) {
    // For each default option...
    Object.keys(options).forEach(function(key) {
      if (!(key in cli.options)) {
        // If this option doesn't exist in the parsed cli.options, add it in.
        cli.options[key] = options[key];
      } else if (cli.optlist[key].type === Array) {
        // If this option's type is Array, append it to any existing array
        // (or create a new array).
        [].push.apply(cli.options[key], options[key]);
      }
    });
  }

  // Run tasks.
  grunt.tasks(cli.tasks, cli.options, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config"></a>[function <span class="apidocSignatureSpan">grunt.</span>config (prop, value)](#apidoc.element.grunt.config)
- description and source-code
```javascript
config = function (prop, value) {
  if (arguments.length === 2) {
    // Two arguments were passed, set the property's value.
    return config.set(prop, value);
  } else {
    // Get the property's value (or the entire data object).
    return config.get(prop);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.fatal"></a>[function <span class="apidocSignatureSpan">grunt.</span>fatal ()](#apidoc.element.grunt.fatal)
- description and source-code
```javascript
fatal = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob"></a>[function <span class="apidocSignatureSpan">grunt.</span>file.glob (pattern, options, cb)](#apidoc.element.grunt.file.glob)
- description and source-code
```javascript
function glob(pattern, options, cb) {
  if (typeof options === 'function') cb = options, options = {}
  if (!options) options = {}

  if (options.sync) {
    if (cb)
      throw new TypeError('callback provided to sync glob')
    return globSync(pattern, options)
  }

  return new Glob(pattern, options, cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch"></a>[function <span class="apidocSignatureSpan">grunt.</span>file.minimatch (p, pattern, options)](#apidoc.element.grunt.file.minimatch)
- description and source-code
```javascript
function minimatch(p, pattern, options) {
  if (typeof pattern !== 'string') {
    throw new TypeError('glob pattern string required')
  }

  if (!options) options = {}

  // shortcut: comments match nothing.
  if (!options.nocomment && pattern.charAt(0) === '#') {
    return false
  }

  // "" only matches ""
  if (pattern.trim() === '') return p === ''

  return new Minimatch(pattern, options).match(p)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.initConfig"></a>[function <span class="apidocSignatureSpan">grunt.</span>initConfig ()](#apidoc.element.grunt.initConfig)
- description and source-code
```javascript
initConfig = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.loadNpmTasks"></a>[function <span class="apidocSignatureSpan">grunt.</span>loadNpmTasks ()](#apidoc.element.grunt.loadNpmTasks)
- description and source-code
```javascript
loadNpmTasks = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.loadTasks"></a>[function <span class="apidocSignatureSpan">grunt.</span>loadTasks ()](#apidoc.element.grunt.loadTasks)
- description and source-code
```javascript
loadTasks = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.option"></a>[function <span class="apidocSignatureSpan">grunt.</span>option (key, value)](#apidoc.element.grunt.option)
- description and source-code
```javascript
option = function (key, value) {
  var no = key.match(/^no-(.+)$/);
  if (arguments.length === 2) {
    return (data[key] = value);
  } else if (no) {
    return data[no[1]] === false;
  } else {
    return data[key];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.registerInitTask"></a>[function <span class="apidocSignatureSpan">grunt.</span>registerInitTask ()](#apidoc.element.grunt.registerInitTask)
- description and source-code
```javascript
registerInitTask = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.registerMultiTask"></a>[function <span class="apidocSignatureSpan">grunt.</span>registerMultiTask ()](#apidoc.element.grunt.registerMultiTask)
- description and source-code
```javascript
registerMultiTask = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.registerTask"></a>[function <span class="apidocSignatureSpan">grunt.</span>registerTask ()](#apidoc.element.grunt.registerTask)
- description and source-code
```javascript
registerTask = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.renameTask"></a>[function <span class="apidocSignatureSpan">grunt.</span>renameTask ()](#apidoc.element.grunt.renameTask)
- description and source-code
```javascript
renameTask = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.tasks"></a>[function <span class="apidocSignatureSpan">grunt.</span>tasks (tasks, options, done)](#apidoc.element.grunt.tasks)
- description and source-code
```javascript
tasks = function (tasks, options, done) {
  // Update options with passed-in options.
  option.init(options);

  // Display the grunt version and quit if the user did --version.
  var _tasks, _options;
  if (option('version')) {
    // Not --verbose.
    log.writeln('grunt v' + grunt.version);

    if (option('verbose')) {
      // --verbose
      verbose.writeln('Install path: ' + path.resolve(__dirname, '..'));
      // Yes, this is a total hack, but we don't want to log all that verbose
      // task initialization stuff here.
      grunt.log.muted = true;
      // Initialize task system so that available tasks can be listed.
      grunt.task.init([], {help: true});
      // Re-enable logging.
      grunt.log.muted = false;

      // Display available tasks (for shell completion, etc).
      _tasks = Object.keys(grunt.task._tasks).sort();
      verbose.writeln('Available tasks: ' + _tasks.join(' '));

      // Display available options (for shell completion, etc).
      _options = [];
      Object.keys(grunt.cli.optlist).forEach(function(long) {
        var o = grunt.cli.optlist[long];
        _options.push('--' + (o.negate ? 'no-' : '') + long);
        if (o.short) { _options.push('-' + o.short); }
      });
      verbose.writeln('Available options: ' + _options.join(' '));
    }

    return;
  }

  // Init colors.
  log.initColors();

  // Display help and quit if the user did --help.
  if (option('help')) {
    help.display();
    return;
  }

  // A little header stuff.
  verbose.header('Initializing').writeflags(option.flags(), 'Command-line options');

  // Determine and output which tasks will be run.
  var tasksSpecified = tasks && tasks.length > 0;
  tasks = task.parseArgs([tasksSpecified ? tasks : 'default']);

  // Initialize tasks.
  task.init(tasks, options);

  verbose.writeln();
  if (!tasksSpecified) {
    verbose.writeln('No tasks specified, running default tasks.');
  }
  verbose.writeflags(tasks, 'Running tasks');

  // Handle otherwise unhandleable (probably asynchronous) exceptions.
  var uncaughtHandler = function(e) {
    fail.fatal(e, fail.code.TASK_FAILURE);
  };
  process.on('uncaughtException', uncaughtHandler);

  // Report, etc when all tasks have completed.
  task.options({
    error: function(e) {
      fail.warn(e, fail.code.TASK_FAILURE);
    },
    done: function() {
      // Stop handling uncaught exceptions so that we don't leave any
      // unwanted process-level side effects behind. There is no need to do
      // this in the error callback, because fail.warn() will either kill
      // the process, or with --force keep on going all the way here.
      process.removeListener('uncaughtException', uncaughtHandler);

      // Output a final fail / success report.
      fail.report();

      if (done) {
        // Execute "done" function when done (only if passed, of course).
        done();
      } else {
        // Otherwise, explicitly exit.
        util.exit(0);
      }
    }
  });

  // Execute all tasks, in order. Passing each task individually in a forEach
  // allows the error callback to execute multiple times.
  tasks.forEach(function(name) { task.run(name); });
  // Run tasks async internally to reduce call-stack, per:
  // https://github.com/gruntjs/grunt/pull/1026
  task.start({asyncDone: true});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.warn"></a>[function <span class="apidocSignatureSpan">grunt.</span>warn ()](#apidoc.element.grunt.warn)
- description and source-code
```javascript
warn = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.config"></a>[module grunt.config](#apidoc.module.grunt.config)

#### <a name="apidoc.element.grunt.config.config"></a>[function <span class="apidocSignatureSpan">grunt.</span>config (prop, value)](#apidoc.element.grunt.config.config)
- description and source-code
```javascript
config = function (prop, value) {
  if (arguments.length === 2) {
    // Two arguments were passed, set the property's value.
    return config.set(prop, value);
  } else {
    // Get the property's value (or the entire data object).
    return config.get(prop);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.escape"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>escape (str)](#apidoc.element.grunt.config.escape)
- description and source-code
```javascript
escape = function (str) {
  return str.replace(/\./g, '\\.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.get"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>get (prop)](#apidoc.element.grunt.config.get)
- description and source-code
```javascript
get = function (prop) {
  return config.process(config.getRaw(prop));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.getPropString"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>getPropString (prop)](#apidoc.element.grunt.config.getPropString)
- description and source-code
```javascript
getPropString = function (prop) {
  return Array.isArray(prop) ? prop.map(config.escape).join('.') : prop;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.getRaw"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>getRaw (prop)](#apidoc.element.grunt.config.getRaw)
- description and source-code
```javascript
getRaw = function (prop) {
  if (prop) {
    // Prop was passed, get that specific property's value.
    return grunt.util.namespace.get(config.data, config.getPropString(prop));
  } else {
    // No prop was passed, return the entire config.data object.
    return config.data;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.init"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>init (obj)](#apidoc.element.grunt.config.init)
- description and source-code
```javascript
init = function (obj) {
  grunt.verbose.write('Initializing config...').ok();
  // Initialize and return data.
  return (config.data = obj || {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.merge"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>merge (obj)](#apidoc.element.grunt.config.merge)
- description and source-code
```javascript
merge = function (obj) {
  grunt.util._.merge(config.data, obj);
  return config.data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.process"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>process (raw)](#apidoc.element.grunt.config.process)
- description and source-code
```javascript
process = function (raw) {
  return grunt.util.recurse(raw, function(value) {
    // If the value is not a string, return it.
    if (typeof value !== 'string') { return value; }
    // If possible, access the specified property via config.get, in case it
    // doesn't refer to a string, but instead refers to an object or array.
    var matches = value.match(propStringTmplRe);
    var result;
    if (matches) {
      result = config.get(matches[1]);
      // If the result retrieved from the config data wasn't null or undefined,
      // return it.
      if (result != null) { return result; }
    }
    // Process the string as a template.
    return grunt.template.process(value, {data: config.data});
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.requires"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>requires ()](#apidoc.element.grunt.config.requires)
- description and source-code
```javascript
requires = function () {
  var p = grunt.util.pluralize;
  var props = grunt.util.toArray(arguments).map(config.getPropString);
  var msg = 'Verifying propert' + p(props.length, 'y/ies') +
    ' ' + grunt.log.wordlist(props) + ' exist' + p(props.length, 's') +
    ' in config...';
  grunt.verbose.write(msg);
  var failProps = config.data && props.filter(function(prop) {
    return config.get(prop) == null;
  }).map(function(prop) {
    return '"' + prop + '"';
  });
  if (config.data && failProps.length === 0) {
    grunt.verbose.ok();
    return true;
  } else {
    grunt.verbose.or.write(msg);
    grunt.log.error().error('Unable to process task.');
    if (!config.data) {
      throw grunt.util.error('Unable to load config.');
    } else {
      throw grunt.util.error('Required config propert' +
        p(failProps.length, 'y/ies') + ' ' + failProps.join(', ') + ' missing.');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.config.set"></a>[function <span class="apidocSignatureSpan">grunt.config.</span>set (prop, value)](#apidoc.element.grunt.config.set)
- description and source-code
```javascript
set = function (prop, value) {
  return grunt.util.namespace.set(config.data, config.getPropString(prop), value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.fail"></a>[module grunt.fail](#apidoc.module.grunt.fail)

#### <a name="apidoc.element.grunt.fail.fatal"></a>[function <span class="apidocSignatureSpan">grunt.fail.</span>fatal (e, errcode)](#apidoc.element.grunt.fail.fatal)
- description and source-code
```javascript
fatal = function (e, errcode) {
  writeln(e, 'fatal');
  dumpStack(e);
  grunt.util.exit(typeof errcode === 'number' ? errcode : fail.code.FATAL_ERROR);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.fail.report"></a>[function <span class="apidocSignatureSpan">grunt.fail.</span>report ()](#apidoc.element.grunt.fail.report)
- description and source-code
```javascript
report = function () {
  if (fail.warncount > 0) {
    grunt.log.writeln().fail('Done, but with warnings.');
  } else {
    grunt.log.writeln().success('Done.');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.fail.warn"></a>[function <span class="apidocSignatureSpan">grunt.fail.</span>warn (e, errcode)](#apidoc.element.grunt.fail.warn)
- description and source-code
```javascript
warn = function (e, errcode) {
  var message = typeof e === 'string' ? e : e.message;
  fail.warncount++;
  writeln(message, 'warn');
  // If -f or --force aren't used, stop script processing.
  if (!grunt.option('force')) {
    dumpStack(e);
    grunt.log.writeln().fail('Aborted due to warnings.');
    grunt.util.exit(typeof errcode === 'number' ? errcode : fail.code.WARNING);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.file"></a>[module grunt.file](#apidoc.module.grunt.file)

#### <a name="apidoc.element.grunt.file._copy"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>_copy (srcpath, destpath, options)](#apidoc.element.grunt.file._copy)
- description and source-code
```javascript
_copy = function (srcpath, destpath, options) {
  if (!options) { options = {}; }
  // If a process function was specified, and noProcess isn't true or doesn't
  // match the srcpath, process the file's source.
  var process = options.process && options.noProcess !== true &&
    !(options.noProcess && file.isMatch(options.noProcess, srcpath));
  // If the file will be processed, use the encoding as-specified. Otherwise,
  // use an encoding of null to force the file to be read/written as a Buffer.
  var readWriteOptions = process ? options : {encoding: null};
  // Actually read the file.
  var contents = file.read(srcpath, readWriteOptions);
  if (process) {
    grunt.verbose.write('Processing source...');
    try {
      contents = options.process(contents, srcpath, destpath);
      grunt.verbose.ok();
    } catch (e) {
      grunt.verbose.error();
      throw grunt.util.error('Error while processing "' + srcpath + '" file.', e);
    }
  }
  // Abort copy if the process function returns false.
  if (contents === false) {
    grunt.verbose.writeln('Write aborted.');
  } else {
    file.write(destpath, contents, readWriteOptions);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.arePathsEquivalent"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>arePathsEquivalent (first)](#apidoc.element.grunt.file.arePathsEquivalent)
- description and source-code
```javascript
arePathsEquivalent = function (first) {
  first = path.resolve(first);
  for (var i = 1; i < arguments.length; i++) {
    if (first !== path.resolve(arguments[i])) { return false; }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.copy"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>copy (srcpath, destpath, options)](#apidoc.element.grunt.file.copy)
- description and source-code
```javascript
function copy(srcpath, destpath, options) {
  if (file.isDir(srcpath)) {
    // Copy a directory, recursively.
    // Explicitly create new dest directory.
    file.mkdir(destpath);
    // Iterate over all sub-files/dirs, recursing.
    fs.readdirSync(srcpath).forEach(function(filepath) {
      copy(path.join(srcpath, filepath), path.join(destpath, filepath), options);
    });
  } else {
    // Copy a single file.
    file._copy(srcpath, destpath, options);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.delete"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>delete (filepath, options)](#apidoc.element.grunt.file.delete)
- description and source-code
```javascript
delete = function (filepath, options) {
  filepath = String(filepath);

  var nowrite = grunt.option('no-write');
  if (!options) {
    options = {force: grunt.option('force') || false};
  }

  grunt.verbose.write((nowrite ? 'Not actually deleting ' : 'Deleting ') + filepath + '...');

  if (!file.exists(filepath)) {
    grunt.verbose.error();
    grunt.log.warn('Cannot delete nonexistent file.');
    return false;
  }

  // Only delete cwd or outside cwd if --force enabled. Be careful, people!
  if (!options.force) {
    if (file.isPathCwd(filepath)) {
      grunt.verbose.error();
      grunt.fail.warn('Cannot delete the current working directory.');
      return false;
    } else if (!file.isPathInCwd(filepath)) {
      grunt.verbose.error();
      grunt.fail.warn('Cannot delete files outside the current working directory.');
      return false;
    }
  }

  try {
    // Actually delete. Or not.
    if (!nowrite) {
      rimraf.sync(filepath);
    }
    grunt.verbose.ok();
    return true;
  } catch (e) {
    grunt.verbose.error();
    throw grunt.util.error('Unable to delete "' + filepath + '" file (' + e.message + ').', e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.doesPathContain"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>doesPathContain (ancestor)](#apidoc.element.grunt.file.doesPathContain)
- description and source-code
```javascript
doesPathContain = function (ancestor) {
  ancestor = path.resolve(ancestor);
  var relative;
  for (var i = 1; i < arguments.length; i++) {
    relative = path.relative(path.resolve(arguments[i]), ancestor);
    if (relative === '' || /\w+/.test(relative)) { return false; }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.exists"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>exists ()](#apidoc.element.grunt.file.exists)
- description and source-code
```javascript
exists = function () {
  var filepath = path.join.apply(path, arguments);
  return fs.existsSync(filepath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.expand"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>expand ()](#apidoc.element.grunt.file.expand)
- description and source-code
```javascript
expand = function () {
  var args = grunt.util.toArray(arguments);
  // If the first argument is an options object, save those options to pass
  // into the file.glob.sync method.
  var options = grunt.util.kindOf(args[0]) === 'object' ? args.shift() : {};
  // Use the first argument if it's an Array, otherwise convert the arguments
  // object to an array and use that.
  var patterns = Array.isArray(args[0]) ? args[0] : args;
  // Return empty set if there are no patterns or filepaths.
  if (patterns.length === 0) { return []; }
  // Return all matching filepaths.
  var matches = processPatterns(patterns, function(pattern) {
    // Find all matching files for this pattern.
    return file.glob.sync(pattern, options);
  });
  // Filter result set?
  if (options.filter) {
    matches = matches.filter(function(filepath) {
      filepath = path.join(options.cwd || '', filepath);
      try {
        if (typeof options.filter === 'function') {
          return options.filter(filepath);
        } else {
          // If the file is of the right type and exists, this should work.
          return fs.statSync(filepath)[options.filter]();
        }
      } catch (e) {
        // Otherwise, it's probably not the right type.
        return false;
      }
    });
  }
  return matches;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.expandMapping"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>expandMapping (patterns, destBase, options)](#apidoc.element.grunt.file.expandMapping)
- description and source-code
```javascript
expandMapping = function (patterns, destBase, options) {
  options = grunt.util._.defaults({}, options, {
    extDot: 'first',
    rename: function(destBase, destPath) {
      return path.join(destBase || '', destPath);
    }
  });
  var files = [];
  var fileByDest = {};
  // Find all files matching pattern, using passed-in options.
  file.expand(options, patterns).forEach(function(src) {
    var destPath = src;
    // Flatten?
    if (options.flatten) {
      destPath = path.basename(destPath);
    }
    // Change the extension?
    if ('ext' in options) {
      destPath = destPath.replace(extDotRe[options.extDot], options.ext);
    }
    // Generate destination filename.
    var dest = options.rename(destBase, destPath, options);
    // Prepend cwd to src path if necessary.
    if (options.cwd) { src = path.join(options.cwd, src); }
    // Normalize filepaths to be unix-style.
    dest = dest.replace(pathSeparatorRe, '/');
    src = src.replace(pathSeparatorRe, '/');
    // Map correct src path to dest path.
    if (fileByDest[dest]) {
      // If dest already exists, push this src onto that dest's src array.
      fileByDest[dest].src.push(src);
    } else {
      // Otherwise create a new src-dest file mapping object.
      files.push({
        src: [src],
        dest: dest,
      });
      // And store a reference for later use.
      fileByDest[dest] = files[files.length - 1];
    }
  });
  return files;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.findup"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>findup (patterns, options)](#apidoc.element.grunt.file.findup)
- description and source-code
```javascript
findup = function (patterns, options) {
  // Normalize patterns to an array.
  if (!Array.isArray(patterns)) { patterns = [patterns]; }
  // Create globOptions so that it can be modified without mutating the
  // original object.
  var globOptions = Object.create(options || {});
  globOptions.maxDepth = 1;
  globOptions.cwd = path.resolve(globOptions.cwd || '.');

  var files, lastpath;
  do {
    // Search for files matching patterns.
    files = patterns.map(function(pattern) {
      return glob.sync(pattern, globOptions);
    }).reduce(function(a, b) {
      return a.concat(b);
    }).filter(function(entry, index, arr) {
      return index === arr.indexOf(entry);
    });
    // Return file if found.
    if (files.length > 0) {
      return path.resolve(path.join(globOptions.cwd, files[0]));
    }
    // Go up a directory.
    lastpath = globOptions.cwd;
    globOptions.cwd = path.resolve(globOptions.cwd, '..');
  // If parentpath is the same as basedir, we can't go any higher.
  } while (globOptions.cwd !== lastpath);

  // No files were found!
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>glob (pattern, options, cb)](#apidoc.element.grunt.file.glob)
- description and source-code
```javascript
function glob(pattern, options, cb) {
  if (typeof options === 'function') cb = options, options = {}
  if (!options) options = {}

  if (options.sync) {
    if (cb)
      throw new TypeError('callback provided to sync glob')
    return globSync(pattern, options)
  }

  return new Glob(pattern, options, cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.isDir"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>isDir ()](#apidoc.element.grunt.file.isDir)
- description and source-code
```javascript
isDir = function () {
  var filepath = path.join.apply(path, arguments);
  return file.exists(filepath) && fs.statSync(filepath).isDirectory();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.isFile"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>isFile ()](#apidoc.element.grunt.file.isFile)
- description and source-code
```javascript
isFile = function () {
  var filepath = path.join.apply(path, arguments);
  return file.exists(filepath) && fs.statSync(filepath).isFile();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.isLink"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>isLink ()](#apidoc.element.grunt.file.isLink)
- description and source-code
```javascript
isLink = function () {
  var filepath = path.join.apply(path, arguments);
  return file.exists(filepath) && fs.lstatSync(filepath).isSymbolicLink();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.isMatch"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>isMatch ()](#apidoc.element.grunt.file.isMatch)
- description and source-code
```javascript
isMatch = function () {
  return file.match.apply(file, arguments).length > 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.isPathAbsolute"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>isPathAbsolute ()](#apidoc.element.grunt.file.isPathAbsolute)
- description and source-code
```javascript
isPathAbsolute = function () {
  var filepath = path.join.apply(path, arguments);
  return pathIsAbsolute(filepath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.isPathCwd"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>isPathCwd ()](#apidoc.element.grunt.file.isPathCwd)
- description and source-code
```javascript
isPathCwd = function () {
  var filepath = path.join.apply(path, arguments);
  try {
    return file.arePathsEquivalent(fs.realpathSync(process.cwd()), fs.realpathSync(filepath));
  } catch (e) {
    return false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.isPathInCwd"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>isPathInCwd ()](#apidoc.element.grunt.file.isPathInCwd)
- description and source-code
```javascript
isPathInCwd = function () {
  var filepath = path.join.apply(path, arguments);
  try {
    return file.doesPathContain(fs.realpathSync(process.cwd()), fs.realpathSync(filepath));
  } catch (e) {
    return false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.match"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>match (options, patterns, filepaths)](#apidoc.element.grunt.file.match)
- description and source-code
```javascript
match = function (options, patterns, filepaths) {
  if (grunt.util.kindOf(options) !== 'object') {
    filepaths = patterns;
    patterns = options;
    options = {};
  }
  // Return empty set if either patterns or filepaths was omitted.
  if (patterns == null || filepaths == null) { return []; }
  // Normalize patterns and filepaths to arrays.
  if (!Array.isArray(patterns)) { patterns = [patterns]; }
  if (!Array.isArray(filepaths)) { filepaths = [filepaths]; }
  // Return empty set if there are no patterns or filepaths.
  if (patterns.length === 0 || filepaths.length === 0) { return []; }
  // Return all matching filepaths.
  return processPatterns(patterns, function(pattern) {
    return file.minimatch.match(filepaths, pattern, options);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>minimatch (p, pattern, options)](#apidoc.element.grunt.file.minimatch)
- description and source-code
```javascript
function minimatch(p, pattern, options) {
  if (typeof pattern !== 'string') {
    throw new TypeError('glob pattern string required')
  }

  if (!options) options = {}

  // shortcut: comments match nothing.
  if (!options.nocomment && pattern.charAt(0) === '#') {
    return false
  }

  // "" only matches ""
  if (pattern.trim() === '') return p === ''

  return new Minimatch(pattern, options).match(p)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.mkdir"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>mkdir (dirpath, mode)](#apidoc.element.grunt.file.mkdir)
- description and source-code
```javascript
mkdir = function (dirpath, mode) {
  if (grunt.option('no-write')) { return; }
  // Set directory mode in a strict-mode-friendly way.
  if (mode == null) {
    mode = parseInt('0777', 8) & (~process.umask());
  }
  dirpath.split(pathSeparatorRe).reduce(function(parts, part) {
    parts += part + '/';
    var subpath = path.resolve(parts);
    if (!file.exists(subpath)) {
      try {
        fs.mkdirSync(subpath, mode);
      } catch (e) {
        throw grunt.util.error('Unable to create directory "' + subpath + '" (Error code: ' + e.code + ').', e);
      }
    }
    return parts;
  }, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.read"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>read (filepath, options)](#apidoc.element.grunt.file.read)
- description and source-code
```javascript
read = function (filepath, options) {
  if (!options) { options = {}; }
  var contents;
  grunt.verbose.write('Reading ' + filepath + '...');
  try {
    contents = fs.readFileSync(String(filepath));
    // If encoding is not explicitly null, convert from encoded buffer to a
    // string. If no encoding was specified, use the default.
    if (options.encoding !== null) {
      contents = iconv.decode(contents, options.encoding || file.defaultEncoding, {stripBOM: !file.preserveBOM});
    }
    grunt.verbose.ok();
    return contents;
  } catch (e) {
    grunt.verbose.error();
    throw grunt.util.error('Unable to read "' + filepath + '" file (Error code: ' + e.code + ').', e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.readJSON"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>readJSON (filepath, options)](#apidoc.element.grunt.file.readJSON)
- description and source-code
```javascript
readJSON = function (filepath, options) {
  var src = file.read(filepath, options);
  var result;
  grunt.verbose.write('Parsing ' + filepath + '...');
  try {
    result = JSON.parse(src);
    grunt.verbose.ok();
    return result;
  } catch (e) {
    grunt.verbose.error();
    throw grunt.util.error('Unable to parse "' + filepath + '" file (' + e.message + ').', e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.readYAML"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>readYAML (filepath, options)](#apidoc.element.grunt.file.readYAML)
- description and source-code
```javascript
readYAML = function (filepath, options) {
  var src = file.read(filepath, options);
  var result;
  grunt.verbose.write('Parsing ' + filepath + '...');
  try {
    result = YAML.load(src);
    grunt.verbose.ok();
    return result;
  } catch (e) {
    grunt.verbose.error();
    throw grunt.util.error('Unable to parse "' + filepath + '" file (' + e.problem + ').', e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.recurse"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>recurse (rootdir, callback, subdir)](#apidoc.element.grunt.file.recurse)
- description and source-code
```javascript
function recurse(rootdir, callback, subdir) {
  var abspath = subdir ? path.join(rootdir, subdir) : rootdir;
  fs.readdirSync(abspath).forEach(function(filename) {
    var filepath = path.join(abspath, filename);
    if (fs.statSync(filepath).isDirectory()) {
      recurse(rootdir, callback, unixifyPath(path.join(subdir || '', filename || '')));
    } else {
      callback(unixifyPath(filepath), rootdir, subdir, filename);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.setBase"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>setBase ()](#apidoc.element.grunt.file.setBase)
- description and source-code
```javascript
setBase = function () {
  var dirpath = path.join.apply(path, arguments);
  process.chdir(dirpath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.write"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>write (filepath, contents, options)](#apidoc.element.grunt.file.write)
- description and source-code
```javascript
write = function (filepath, contents, options) {
  if (!options) { options = {}; }
  var nowrite = grunt.option('no-write');
  grunt.verbose.write((nowrite ? 'Not actually writing ' : 'Writing ') + filepath + '...');
  // Create path, if necessary.
  file.mkdir(path.dirname(filepath));
  try {
    // If contents is already a Buffer, don't try to encode it. If no encoding
    // was specified, use the default.
    if (!Buffer.isBuffer(contents)) {
      contents = iconv.encode(contents, options.encoding || file.defaultEncoding);
    }
    // Actually write file.
    if (!nowrite) {
      fs.writeFileSync(filepath, contents, 'mode' in options ? {mode: options.mode} : {});
    }
    grunt.verbose.ok();
    return true;
  } catch (e) {
    grunt.verbose.error();
    throw grunt.util.error('Unable to write "' + filepath + '" file (Error code: ' + e.code + ').', e);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.file.glob"></a>[module grunt.file.glob](#apidoc.module.grunt.file.glob)

#### <a name="apidoc.element.grunt.file.glob.glob"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>glob (pattern, options, cb)](#apidoc.element.grunt.file.glob.glob)
- description and source-code
```javascript
function glob(pattern, options, cb) {
  if (typeof options === 'function') cb = options, options = {}
  if (!options) options = {}

  if (options.sync) {
    if (cb)
      throw new TypeError('callback provided to sync glob')
    return globSync(pattern, options)
  }

  return new Glob(pattern, options, cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.</span>Glob (pattern, options, cb)](#apidoc.element.grunt.file.glob.Glob)
- description and source-code
```javascript
function Glob(pattern, options, cb) {
  if (typeof options === 'function') {
    cb = options
    options = null
  }

  if (options && options.sync) {
    if (cb)
      throw new TypeError('callback provided to sync glob')
    return new GlobSync(pattern, options)
  }

  if (!(this instanceof Glob))
    return new Glob(pattern, options, cb)

  setopts(this, pattern, options)
  this._didRealPath = false

  // process each pattern in the minimatch set
  var n = this.minimatch.set.length

  // The matches are stored as {<filename>: true,...} so that
  // duplicates are automagically pruned.
  // Later, we do an Object.keys() on these.
  // Keep them as a list so we can fill in when nonull is set.
  this.matches = new Array(n)

  if (typeof cb === 'function') {
    cb = once(cb)
    this.on('error', cb)
    this.on('end', function (matches) {
      cb(null, matches)
    })
  }

  var self = this
  var n = this.minimatch.set.length
  this._processing = 0
  this.matches = new Array(n)

  this._emitQueue = []
  this._processQueue = []
  this.paused = false

  if (this.noprocess)
    return this

  if (n === 0)
    return done()

  var sync = true
  for (var i = 0; i < n; i ++) {
    this._process(this.minimatch.set[i], i, false, done)
  }
  sync = false

  function done () {
    --self._processing
    if (self._processing <= 0) {
      if (sync) {
        process.nextTick(function () {
          self._finish()
        })
      } else {
        self._finish()
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.</span>GlobSync (pattern, options)](#apidoc.element.grunt.file.glob.GlobSync)
- description and source-code
```javascript
function GlobSync(pattern, options) {
  if (!pattern)
    throw new Error('must provide pattern')

  if (typeof options === 'function' || arguments.length === 3)
    throw new TypeError('callback provided to sync glob\n'+
                        'See: https://github.com/isaacs/node-glob/issues/167')

  if (!(this instanceof GlobSync))
    return new GlobSync(pattern, options)

  setopts(this, pattern, options)

  if (this.noprocess)
    return this

  var n = this.minimatch.set.length
  this.matches = new Array(n)
  for (var i = 0; i < n; i ++) {
    this._process(this.minimatch.set[i], i, false)
  }
  this._finish()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.hasMagic"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.</span>hasMagic (pattern, options_)](#apidoc.element.grunt.file.glob.hasMagic)
- description and source-code
```javascript
hasMagic = function (pattern, options_) {
  var options = extend({}, options_)
  options.noprocess = true

  var g = new Glob(pattern, options)
  var set = g.minimatch.set

  if (!pattern)
    return false

  if (set.length > 1)
    return true

  for (var j = 0; j < set[0].length; j++) {
    if (typeof set[0][j] !== 'string')
      return true
  }

  return false
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.sync"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.</span>sync (pattern, options)](#apidoc.element.grunt.file.glob.sync)
- description and source-code
```javascript
function globSync(pattern, options) {
  if (typeof options === 'function' || arguments.length === 3)
    throw new TypeError('callback provided to sync glob\n'+
                        'See: https://github.com/isaacs/node-glob/issues/167')

  return new GlobSync(pattern, options).found
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.file.glob.Glob.prototype"></a>[module grunt.file.glob.Glob.prototype](#apidoc.module.grunt.file.glob.Glob.prototype)

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._emitMatch"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_emitMatch (index, e)](#apidoc.element.grunt.file.glob.Glob.prototype._emitMatch)
- description and source-code
```javascript
_emitMatch = function (index, e) {
  if (this.aborted)
    return

  if (this.matches[index][e])
    return

  if (isIgnored(this, e))
    return

  if (this.paused) {
    this._emitQueue.push([index, e])
    return
  }

  var abs = this._makeAbs(e)

  if (this.nodir) {
    var c = this.cache[abs]
    if (c === 'DIR' || Array.isArray(c))
      return
  }

  if (this.mark)
    e = this._mark(e)

  this.matches[index][e] = true

  var st = this.statCache[abs]
  if (st)
    this.emit('stat', e, st)

  this.emit('match', e)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._finish"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_finish ()](#apidoc.element.grunt.file.glob.Glob.prototype._finish)
- description and source-code
```javascript
_finish = function () {
  assert(this instanceof Glob)
  if (this.aborted)
    return

  if (this.realpath && !this._didRealpath)
    return this._realpath()

  common.finish(this)
  this.emit('end', this.found)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._makeAbs"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_makeAbs (f)](#apidoc.element.grunt.file.glob.Glob.prototype._makeAbs)
- description and source-code
```javascript
_makeAbs = function (f) {
  return common.makeAbs(this, f)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._mark"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_mark (p)](#apidoc.element.grunt.file.glob.Glob.prototype._mark)
- description and source-code
```javascript
_mark = function (p) {
  return common.mark(this, p)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._process"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_process (pattern, index, inGlobStar, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._process)
- description and source-code
```javascript
_process = function (pattern, index, inGlobStar, cb) {
  assert(this instanceof Glob)
  assert(typeof cb === 'function')

  if (this.aborted)
    return

  this._processing++
  if (this.paused) {
    this._processQueue.push([pattern, index, inGlobStar, cb])
    return
  }

  //console.error('PROCESS %d', this._processing, pattern)

  // Get the first [n] parts of pattern that are all strings.
  var n = 0
  while (typeof pattern[n] === 'string') {
    n ++
  }
  // now n is the index of the first one that is *not* a string.

  // see if there's anything else
  var prefix
  switch (n) {
    // if not, then this is rather simple
    case pattern.length:
      this._processSimple(pattern.join('/'), index, cb)
      return

    case 0:
      // pattern *starts* with some non-trivial item.
      // going to readdir(cwd), but not include the prefix in matches.
      prefix = null
      break

    default:
      // pattern has some string bits in the front.
      // whatever it starts with, whether that's 'absolute' like /foo/bar,
      // or 'relative' like '../baz'
      prefix = pattern.slice(0, n).join('/')
      break
  }

  var remain = pattern.slice(n)

  // get the list of entries.
  var read
  if (prefix === null)
    read = '.'
  else if (isAbsolute(prefix) || isAbsolute(pattern.join('/'))) {
    if (!prefix || !isAbsolute(prefix))
      prefix = '/' + prefix
    read = prefix
  } else
    read = prefix

  var abs = this._makeAbs(read)

  //if ignored, skip _processing
  if (childrenIgnored(this, read))
    return cb()

  var isGlobStar = remain[0] === minimatch.GLOBSTAR
  if (isGlobStar)
    this._processGlobStar(prefix, read, abs, remain, index, inGlobStar, cb)
  else
    this._processReaddir(prefix, read, abs, remain, index, inGlobStar, cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._processGlobStar"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processGlobStar (prefix, read, abs, remain, index, inGlobStar, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processGlobStar)
- description and source-code
```javascript
_processGlobStar = function (prefix, read, abs, remain, index, inGlobStar, cb) {
  var self = this
  this._readdir(abs, inGlobStar, function (er, entries) {
    self._processGlobStar2(prefix, read, abs, remain, index, inGlobStar, entries, cb)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._processGlobStar2"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processGlobStar2 (prefix, read, abs, remain, index, inGlobStar, entries, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processGlobStar2)
- description and source-code
```javascript
_processGlobStar2 = function (prefix, read, abs, remain, index, inGlobStar, entries, cb) {
  //console.error('pgs2', prefix, remain[0], entries)

  // no entries means not a dir, so it can never have matches
  // foo.txt/** doesn't match foo.txt
  if (!entries)
    return cb()

  // test without the globstar, and with every child both below
  // and replacing the globstar.
  var remainWithoutGlobStar = remain.slice(1)
  var gspref = prefix ? [ prefix ] : []
  var noGlobStar = gspref.concat(remainWithoutGlobStar)

  // the noGlobStar pattern exits the inGlobStar state
  this._process(noGlobStar, index, false, cb)

  var isSym = this.symlinks[abs]
  var len = entries.length

  // If it's a symlink, and we're in a globstar, then stop
  if (isSym && inGlobStar)
    return cb()

  for (var i = 0; i < len; i++) {
    var e = entries[i]
    if (e.charAt(0) === '.' && !this.dot)
      continue

    // these two cases enter the inGlobStar state
    var instead = gspref.concat(entries[i], remainWithoutGlobStar)
    this._process(instead, index, true, cb)

    var below = gspref.concat(entries[i], remain)
    this._process(below, index, true, cb)
  }

  cb()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._processReaddir"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processReaddir (prefix, read, abs, remain, index, inGlobStar, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processReaddir)
- description and source-code
```javascript
_processReaddir = function (prefix, read, abs, remain, index, inGlobStar, cb) {
  var self = this
  this._readdir(abs, inGlobStar, function (er, entries) {
    return self._processReaddir2(prefix, read, abs, remain, index, inGlobStar, entries, cb)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._processReaddir2"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processReaddir2 (prefix, read, abs, remain, index, inGlobStar, entries, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processReaddir2)
- description and source-code
```javascript
_processReaddir2 = function (prefix, read, abs, remain, index, inGlobStar, entries, cb) {

  // if the abs isn't a dir, then nothing can match!
  if (!entries)
    return cb()

  // It will only match dot entries if it starts with a dot, or if
  // dot is set.  Stuff like @(.foo|.bar) isn't allowed.
  var pn = remain[0]
  var negate = !!this.minimatch.negate
  var rawGlob = pn._glob
  var dotOk = this.dot || rawGlob.charAt(0) === '.'

  var matchedEntries = []
  for (var i = 0; i < entries.length; i++) {
    var e = entries[i]
    if (e.charAt(0) !== '.' || dotOk) {
      var m
      if (negate && !prefix) {
        m = !e.match(pn)
      } else {
        m = e.match(pn)
      }
      if (m)
        matchedEntries.push(e)
    }
  }

  //console.error('prd2', prefix, entries, remain[0]._glob, matchedEntries)

  var len = matchedEntries.length
  // If there are no matched entries, then nothing matches.
  if (len === 0)
    return cb()

  // if this is the last remaining pattern bit, then no need for
  // an additional stat *unless* the user has specified mark or
  // stat explicitly.  We know they exist, since readdir returned
  // them.

  if (remain.length === 1 && !this.mark && !this.stat) {
    if (!this.matches[index])
      this.matches[index] = Object.create(null)

    for (var i = 0; i < len; i ++) {
      var e = matchedEntries[i]
      if (prefix) {
        if (prefix !== '/')
          e = prefix + '/' + e
        else
          e = prefix + e
      }

      if (e.charAt(0) === '/' && !this.nomount) {
        e = path.join(this.root, e)
      }
      this._emitMatch(index, e)
    }
    // This was the last one, and no stats were needed
    return cb()
  }

  // now test all matched entries as stand-ins for that part
  // of the pattern.
  remain.shift()
  for (var i = 0; i < len; i ++) {
    var e = matchedEntries[i]
    var newPattern
    if (prefix) {
      if (prefix !== '/')
        e = prefix + '/' + e
      else
        e = prefix + e
    }
    this._process([e].concat(remain), index, inGlobStar, cb)
  }
  cb()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._processSimple"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processSimple (prefix, index, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processSimple)
- description and source-code
```javascript
_processSimple = function (prefix, index, cb) {
  // XXX review this.  Shouldn't it be doing the mounting etc
  // before doing stat?  kinda weird?
  var self = this
  this._stat(prefix, function (er, exists) {
    self._processSimple2(prefix, index, er, exists, cb)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._processSimple2"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_processSimple2 (prefix, index, er, exists, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._processSimple2)
- description and source-code
```javascript
_processSimple2 = function (prefix, index, er, exists, cb) {

  //console.error('ps2', prefix, exists)

  if (!this.matches[index])
    this.matches[index] = Object.create(null)

  // If it doesn't exist, then just mark the lack of results
  if (!exists)
    return cb()

  if (prefix && isAbsolute(prefix) && !this.nomount) {
    var trail = /[\/\\]$/.test(prefix)
    if (prefix.charAt(0) === '/') {
      prefix = path.join(this.root, prefix)
    } else {
      prefix = path.resolve(this.root, prefix)
      if (trail)
        prefix += '/'
    }
  }

  if (process.platform === 'win32')
    prefix = prefix.replace(/\\/g, '/')

  // Mark this as a match
  this._emitMatch(index, prefix)
  cb()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._readdir"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_readdir (abs, inGlobStar, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._readdir)
- description and source-code
```javascript
_readdir = function (abs, inGlobStar, cb) {
  if (this.aborted)
    return

  cb = inflight('readdir\0'+abs+'\0'+inGlobStar, cb)
  if (!cb)
    return

  //console.error('RD %j %j', +inGlobStar, abs)
  if (inGlobStar && !ownProp(this.symlinks, abs))
    return this._readdirInGlobStar(abs, cb)

  if (ownProp(this.cache, abs)) {
    var c = this.cache[abs]
    if (!c || c === 'FILE')
      return cb()

    if (Array.isArray(c))
      return cb(null, c)
  }

  var self = this
  fs.readdir(abs, readdirCb(this, abs, cb))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._readdirEntries"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_readdirEntries (abs, entries, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._readdirEntries)
- description and source-code
```javascript
_readdirEntries = function (abs, entries, cb) {
  if (this.aborted)
    return

  // if we haven't asked to stat everything, then just
  // assume that everything in there exists, so we can avoid
  // having to stat it a second time.
  if (!this.mark && !this.stat) {
    for (var i = 0; i < entries.length; i ++) {
      var e = entries[i]
      if (abs === '/')
        e = abs + e
      else
        e = abs + '/' + e
      this.cache[e] = true
    }
  }

  this.cache[abs] = entries
  return cb(null, entries)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._readdirError"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_readdirError (f, er, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._readdirError)
- description and source-code
```javascript
_readdirError = function (f, er, cb) {
  if (this.aborted)
    return

  // handle errors, and cache the information
  switch (er.code) {
    case 'ENOTSUP': // https://github.com/isaacs/node-glob/issues/205
    case 'ENOTDIR': // totally normal. means it *does* exist.
      var abs = this._makeAbs(f)
      this.cache[abs] = 'FILE'
      if (abs === this.cwdAbs) {
        var error = new Error(er.code + ' invalid cwd ' + this.cwd)
        error.path = this.cwd
        error.code = er.code
        this.emit('error', error)
        this.abort()
      }
      break

    case 'ENOENT': // not terribly unusual
    case 'ELOOP':
    case 'ENAMETOOLONG':
    case 'UNKNOWN':
      this.cache[this._makeAbs(f)] = false
      break

    default: // some unusual error.  Treat as failure.
      this.cache[this._makeAbs(f)] = false
      if (this.strict) {
        this.emit('error', er)
        // If the error is handled, then we abort
        // if not, we threw out of here
        this.abort()
      }
      if (!this.silent)
        console.error('glob error', er)
      break
  }

  return cb()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._readdirInGlobStar"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_readdirInGlobStar (abs, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._readdirInGlobStar)
- description and source-code
```javascript
_readdirInGlobStar = function (abs, cb) {
  if (this.aborted)
    return

  // follow all symlinked directories forever
  // just proceed as if this is a non-globstar situation
  if (this.follow)
    return this._readdir(abs, false, cb)

  var lstatkey = 'lstat\0' + abs
  var self = this
  var lstatcb = inflight(lstatkey, lstatcb_)

  if (lstatcb)
    fs.lstat(abs, lstatcb)

  function lstatcb_ (er, lstat) {
    if (er)
      return cb()

    var isSym = lstat.isSymbolicLink()
    self.symlinks[abs] = isSym

    // If it's not a symlink or a dir, then it's definitely a regular file.
    // don't bother doing a readdir in that case.
    if (!isSym && !lstat.isDirectory()) {
      self.cache[abs] = 'FILE'
      cb()
    } else
      self._readdir(abs, false, cb)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._realpath"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_realpath ()](#apidoc.element.grunt.file.glob.Glob.prototype._realpath)
- description and source-code
```javascript
_realpath = function () {
  if (this._didRealpath)
    return

  this._didRealpath = true

  var n = this.matches.length
  if (n === 0)
    return this._finish()

  var self = this
  for (var i = 0; i < this.matches.length; i++)
    this._realpathSet(i, next)

  function next () {
    if (--n === 0)
      self._finish()
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._realpathSet"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_realpathSet (index, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._realpathSet)
- description and source-code
```javascript
_realpathSet = function (index, cb) {
  var matchset = this.matches[index]
  if (!matchset)
    return cb()

  var found = Object.keys(matchset)
  var self = this
  var n = found.length

  if (n === 0)
    return cb()

  var set = this.matches[index] = Object.create(null)
  found.forEach(function (p, i) {
    // If there's a problem with the stat, then it means that
    // one or more of the links in the realpath couldn't be
    // resolved.  just return the abs value in that case.
    p = self._makeAbs(p)
    rp.realpath(p, self.realpathCache, function (er, real) {
      if (!er)
        set[real] = true
      else if (er.syscall === 'stat')
        set[p] = true
      else
        self.emit('error', er) // srsly wtf right here

      if (--n === 0) {
        self.matches[index] = set
        cb()
      }
    })
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._stat"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_stat (f, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._stat)
- description and source-code
```javascript
_stat = function (f, cb) {
  var abs = this._makeAbs(f)
  var needDir = f.slice(-1) === '/'

  if (f.length > this.maxLength)
    return cb()

  if (!this.stat && ownProp(this.cache, abs)) {
    var c = this.cache[abs]

    if (Array.isArray(c))
      c = 'DIR'

    // It exists, but maybe not how we need it
    if (!needDir || c === 'DIR')
      return cb(null, c)

    if (needDir && c === 'FILE')
      return cb()

    // otherwise we have to stat, because maybe c=true
    // if we know it exists, but not what it is.
  }

  var exists
  var stat = this.statCache[abs]
  if (stat !== undefined) {
    if (stat === false)
      return cb(null, stat)
    else {
      var type = stat.isDirectory() ? 'DIR' : 'FILE'
      if (needDir && type === 'FILE')
        return cb()
      else
        return cb(null, type, stat)
    }
  }

  var self = this
  var statcb = inflight('stat\0' + abs, lstatcb_)
  if (statcb)
    fs.lstat(abs, statcb)

  function lstatcb_ (er, lstat) {
    if (lstat && lstat.isSymbolicLink()) {
      // If it's a symlink, then treat it as the target, unless
      // the target does not exist, then treat it as a file.
      return fs.stat(abs, function (er, stat) {
        if (er)
          self._stat2(f, abs, null, lstat, cb)
        else
          self._stat2(f, abs, er, stat, cb)
      })
    } else {
      self._stat2(f, abs, er, lstat, cb)
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype._stat2"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>_stat2 (f, abs, er, stat, cb)](#apidoc.element.grunt.file.glob.Glob.prototype._stat2)
- description and source-code
```javascript
_stat2 = function (f, abs, er, stat, cb) {
  if (er) {
    this.statCache[abs] = false
    return cb()
  }

  var needDir = f.slice(-1) === '/'
  this.statCache[abs] = stat

  if (abs.slice(-1) === '/' && !stat.isDirectory())
    return cb(null, false, stat)

  var c = stat.isDirectory() ? 'DIR' : 'FILE'
  this.cache[abs] = this.cache[abs] || c

  if (needDir && c !== 'DIR')
    return cb()

  return cb(null, c, stat)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype.abort"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>abort ()](#apidoc.element.grunt.file.glob.Glob.prototype.abort)
- description and source-code
```javascript
abort = function () {
  this.aborted = true
  this.emit('abort')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype.pause"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>pause ()](#apidoc.element.grunt.file.glob.Glob.prototype.pause)
- description and source-code
```javascript
pause = function () {
  if (!this.paused) {
    this.paused = true
    this.emit('pause')
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.Glob.prototype.resume"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.Glob.prototype.</span>resume ()](#apidoc.element.grunt.file.glob.Glob.prototype.resume)
- description and source-code
```javascript
resume = function () {
  if (this.paused) {
    this.emit('resume')
    this.paused = false
    if (this._emitQueue.length) {
      var eq = this._emitQueue.slice(0)
      this._emitQueue.length = 0
      for (var i = 0; i < eq.length; i ++) {
        var e = eq[i]
        this._emitMatch(e[0], e[1])
      }
    }
    if (this._processQueue.length) {
      var pq = this._processQueue.slice(0)
      this._processQueue.length = 0
      for (var i = 0; i < pq.length; i ++) {
        var p = pq[i]
        this._processing--
        this._process(p[0], p[1], p[2], p[3])
      }
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.file.glob.GlobSync.prototype"></a>[module grunt.file.glob.GlobSync.prototype](#apidoc.module.grunt.file.glob.GlobSync.prototype)

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._emitMatch"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_emitMatch (index, e)](#apidoc.element.grunt.file.glob.GlobSync.prototype._emitMatch)
- description and source-code
```javascript
_emitMatch = function (index, e) {
  var abs = this._makeAbs(e)
  if (this.mark)
    e = this._mark(e)

  if (this.matches[index][e])
    return

  if (this.nodir) {
    var c = this.cache[this._makeAbs(e)]
    if (c === 'DIR' || Array.isArray(c))
      return
  }

  this.matches[index][e] = true
  if (this.stat)
    this._stat(e)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._finish"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_finish ()](#apidoc.element.grunt.file.glob.GlobSync.prototype._finish)
- description and source-code
```javascript
_finish = function () {
  assert(this instanceof GlobSync)
  if (this.realpath) {
    var self = this
    this.matches.forEach(function (matchset, index) {
      var set = self.matches[index] = Object.create(null)
      for (var p in matchset) {
        try {
          p = self._makeAbs(p)
          var real = rp.realpathSync(p, self.realpathCache)
          set[real] = true
        } catch (er) {
          if (er.syscall === 'stat')
            set[self._makeAbs(p)] = true
          else
            throw er
        }
      }
    })
  }
  common.finish(this)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._makeAbs"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_makeAbs (f)](#apidoc.element.grunt.file.glob.GlobSync.prototype._makeAbs)
- description and source-code
```javascript
_makeAbs = function (f) {
  return common.makeAbs(this, f)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._mark"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_mark (p)](#apidoc.element.grunt.file.glob.GlobSync.prototype._mark)
- description and source-code
```javascript
_mark = function (p) {
  return common.mark(this, p)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._process"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_process (pattern, index, inGlobStar)](#apidoc.element.grunt.file.glob.GlobSync.prototype._process)
- description and source-code
```javascript
_process = function (pattern, index, inGlobStar) {
  assert(this instanceof GlobSync)

  // Get the first [n] parts of pattern that are all strings.
  var n = 0
  while (typeof pattern[n] === 'string') {
    n ++
  }
  // now n is the index of the first one that is *not* a string.

  // See if there's anything else
  var prefix
  switch (n) {
    // if not, then this is rather simple
    case pattern.length:
      this._processSimple(pattern.join('/'), index)
      return

    case 0:
      // pattern *starts* with some non-trivial item.
      // going to readdir(cwd), but not include the prefix in matches.
      prefix = null
      break

    default:
      // pattern has some string bits in the front.
      // whatever it starts with, whether that's 'absolute' like /foo/bar,
      // or 'relative' like '../baz'
      prefix = pattern.slice(0, n).join('/')
      break
  }

  var remain = pattern.slice(n)

  // get the list of entries.
  var read
  if (prefix === null)
    read = '.'
  else if (isAbsolute(prefix) || isAbsolute(pattern.join('/'))) {
    if (!prefix || !isAbsolute(prefix))
      prefix = '/' + prefix
    read = prefix
  } else
    read = prefix

  var abs = this._makeAbs(read)

  //if ignored, skip processing
  if (childrenIgnored(this, read))
    return

  var isGlobStar = remain[0] === minimatch.GLOBSTAR
  if (isGlobStar)
    this._processGlobStar(prefix, read, abs, remain, index, inGlobStar)
  else
    this._processReaddir(prefix, read, abs, remain, index, inGlobStar)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._processGlobStar"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_processGlobStar (prefix, read, abs, remain, index, inGlobStar)](#apidoc.element.grunt.file.glob.GlobSync.prototype._processGlobStar)
- description and source-code
```javascript
_processGlobStar = function (prefix, read, abs, remain, index, inGlobStar) {

  var entries = this._readdir(abs, inGlobStar)

  // no entries means not a dir, so it can never have matches
  // foo.txt/** doesn't match foo.txt
  if (!entries)
    return

  // test without the globstar, and with every child both below
  // and replacing the globstar.
  var remainWithoutGlobStar = remain.slice(1)
  var gspref = prefix ? [ prefix ] : []
  var noGlobStar = gspref.concat(remainWithoutGlobStar)

  // the noGlobStar pattern exits the inGlobStar state
  this._process(noGlobStar, index, false)

  var len = entries.length
  var isSym = this.symlinks[abs]

  // If it's a symlink, and we're in a globstar, then stop
  if (isSym && inGlobStar)
    return

  for (var i = 0; i < len; i++) {
    var e = entries[i]
    if (e.charAt(0) === '.' && !this.dot)
      continue

    // these two cases enter the inGlobStar state
    var instead = gspref.concat(entries[i], remainWithoutGlobStar)
    this._process(instead, index, true)

    var below = gspref.concat(entries[i], remain)
    this._process(below, index, true)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._processReaddir"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_processReaddir (prefix, read, abs, remain, index, inGlobStar)](#apidoc.element.grunt.file.glob.GlobSync.prototype._processReaddir)
- description and source-code
```javascript
_processReaddir = function (prefix, read, abs, remain, index, inGlobStar) {
  var entries = this._readdir(abs, inGlobStar)

  // if the abs isn't a dir, then nothing can match!
  if (!entries)
    return

  // It will only match dot entries if it starts with a dot, or if
  // dot is set.  Stuff like @(.foo|.bar) isn't allowed.
  var pn = remain[0]
  var negate = !!this.minimatch.negate
  var rawGlob = pn._glob
  var dotOk = this.dot || rawGlob.charAt(0) === '.'

  var matchedEntries = []
  for (var i = 0; i < entries.length; i++) {
    var e = entries[i]
    if (e.charAt(0) !== '.' || dotOk) {
      var m
      if (negate && !prefix) {
        m = !e.match(pn)
      } else {
        m = e.match(pn)
      }
      if (m)
        matchedEntries.push(e)
    }
  }

  var len = matchedEntries.length
  // If there are no matched entries, then nothing matches.
  if (len === 0)
    return

  // if this is the last remaining pattern bit, then no need for
  // an additional stat *unless* the user has specified mark or
  // stat explicitly.  We know they exist, since readdir returned
  // them.

  if (remain.length === 1 && !this.mark && !this.stat) {
    if (!this.matches[index])
      this.matches[index] = Object.create(null)

    for (var i = 0; i < len; i ++) {
      var e = matchedEntries[i]
      if (prefix) {
        if (prefix.slice(-1) !== '/')
          e = prefix + '/' + e
        else
          e = prefix + e
      }

      if (e.charAt(0) === '/' && !this.nomount) {
        e = path.join(this.root, e)
      }
      this.matches[index][e] = true
    }
    // This was the last one, and no stats were needed
    return
  }

  // now test all matched entries as stand-ins for that part
  // of the pattern.
  remain.shift()
  for (var i = 0; i < len; i ++) {
    var e = matchedEntries[i]
    var newPattern
    if (prefix)
      newPattern = [prefix, e]
    else
      newPattern = [e]
    this._process(newPattern.concat(remain), index, inGlobStar)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._processSimple"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_processSimple (prefix, index)](#apidoc.element.grunt.file.glob.GlobSync.prototype._processSimple)
- description and source-code
```javascript
_processSimple = function (prefix, index) {
  // XXX review this.  Shouldn't it be doing the mounting etc
  // before doing stat?  kinda weird?
  var exists = this._stat(prefix)

  if (!this.matches[index])
    this.matches[index] = Object.create(null)

  // If it doesn't exist, then just mark the lack of results
  if (!exists)
    return

  if (prefix && isAbsolute(prefix) && !this.nomount) {
    var trail = /[\/\\]$/.test(prefix)
    if (prefix.charAt(0) === '/') {
      prefix = path.join(this.root, prefix)
    } else {
      prefix = path.resolve(this.root, prefix)
      if (trail)
        prefix += '/'
    }
  }

  if (process.platform === 'win32')
    prefix = prefix.replace(/\\/g, '/')

  // Mark this as a match
  this.matches[index][prefix] = true
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._readdir"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_readdir (abs, inGlobStar)](#apidoc.element.grunt.file.glob.GlobSync.prototype._readdir)
- description and source-code
```javascript
_readdir = function (abs, inGlobStar) {
  var entries

  if (inGlobStar && !ownProp(this.symlinks, abs))
    return this._readdirInGlobStar(abs)

  if (ownProp(this.cache, abs)) {
    var c = this.cache[abs]
    if (!c || c === 'FILE')
      return null

    if (Array.isArray(c))
      return c
  }

  try {
    return this._readdirEntries(abs, fs.readdirSync(abs))
  } catch (er) {
    this._readdirError(abs, er)
    return null
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._readdirEntries"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_readdirEntries (abs, entries)](#apidoc.element.grunt.file.glob.GlobSync.prototype._readdirEntries)
- description and source-code
```javascript
_readdirEntries = function (abs, entries) {
  // if we haven't asked to stat everything, then just
  // assume that everything in there exists, so we can avoid
  // having to stat it a second time.
  if (!this.mark && !this.stat) {
    for (var i = 0; i < entries.length; i ++) {
      var e = entries[i]
      if (abs === '/')
        e = abs + e
      else
        e = abs + '/' + e
      this.cache[e] = true
    }
  }

  this.cache[abs] = entries

  // mark and cache dir-ness
  return entries
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._readdirError"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_readdirError (f, er)](#apidoc.element.grunt.file.glob.GlobSync.prototype._readdirError)
- description and source-code
```javascript
_readdirError = function (f, er) {
  // handle errors, and cache the information
  switch (er.code) {
    case 'ENOTSUP': // https://github.com/isaacs/node-glob/issues/205
    case 'ENOTDIR': // totally normal. means it *does* exist.
      var abs = this._makeAbs(f)
      this.cache[abs] = 'FILE'
      if (abs === this.cwdAbs) {
        var error = new Error(er.code + ' invalid cwd ' + this.cwd)
        error.path = this.cwd
        error.code = er.code
        throw error
      }
      break

    case 'ENOENT': // not terribly unusual
    case 'ELOOP':
    case 'ENAMETOOLONG':
    case 'UNKNOWN':
      this.cache[this._makeAbs(f)] = false
      break

    default: // some unusual error.  Treat as failure.
      this.cache[this._makeAbs(f)] = false
      if (this.strict)
        throw er
      if (!this.silent)
        console.error('glob error', er)
      break
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._readdirInGlobStar"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_readdirInGlobStar (abs)](#apidoc.element.grunt.file.glob.GlobSync.prototype._readdirInGlobStar)
- description and source-code
```javascript
_readdirInGlobStar = function (abs) {
  // follow all symlinked directories forever
  // just proceed as if this is a non-globstar situation
  if (this.follow)
    return this._readdir(abs, false)

  var entries
  var lstat
  var stat
  try {
    lstat = fs.lstatSync(abs)
  } catch (er) {
    // lstat failed, doesn't exist
    return null
  }

  var isSym = lstat.isSymbolicLink()
  this.symlinks[abs] = isSym

  // If it's not a symlink or a dir, then it's definitely a regular file.
  // don't bother doing a readdir in that case.
  if (!isSym && !lstat.isDirectory())
    this.cache[abs] = 'FILE'
  else
    entries = this._readdir(abs, false)

  return entries
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.glob.GlobSync.prototype._stat"></a>[function <span class="apidocSignatureSpan">grunt.file.glob.GlobSync.prototype.</span>_stat (f)](#apidoc.element.grunt.file.glob.GlobSync.prototype._stat)
- description and source-code
```javascript
_stat = function (f) {
  var abs = this._makeAbs(f)
  var needDir = f.slice(-1) === '/'

  if (f.length > this.maxLength)
    return false

  if (!this.stat && ownProp(this.cache, abs)) {
    var c = this.cache[abs]

    if (Array.isArray(c))
      c = 'DIR'

    // It exists, but maybe not how we need it
    if (!needDir || c === 'DIR')
      return c

    if (needDir && c === 'FILE')
      return false

    // otherwise we have to stat, because maybe c=true
    // if we know it exists, but not what it is.
  }

  var exists
  var stat = this.statCache[abs]
  if (!stat) {
    var lstat
    try {
      lstat = fs.lstatSync(abs)
    } catch (er) {
      return false
    }

    if (lstat.isSymbolicLink()) {
      try {
        stat = fs.statSync(abs)
      } catch (er) {
        stat = lstat
      }
    } else {
      stat = lstat
    }
  }

  this.statCache[abs] = stat

  var c = stat.isDirectory() ? 'DIR' : 'FILE'
  this.cache[abs] = this.cache[abs] || c

  if (needDir && c !== 'DIR')
    return false

  return c
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.file.minimatch"></a>[module grunt.file.minimatch](#apidoc.module.grunt.file.minimatch)

#### <a name="apidoc.element.grunt.file.minimatch.minimatch"></a>[function <span class="apidocSignatureSpan">grunt.file.</span>minimatch (p, pattern, options)](#apidoc.element.grunt.file.minimatch.minimatch)
- description and source-code
```javascript
function minimatch(p, pattern, options) {
  if (typeof pattern !== 'string') {
    throw new TypeError('glob pattern string required')
  }

  if (!options) options = {}

  // shortcut: comments match nothing.
  if (!options.nocomment && pattern.charAt(0) === '#') {
    return false
  }

  // "" only matches ""
  if (pattern.trim() === '') return p === ''

  return new Minimatch(pattern, options).match(p)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>Minimatch (pattern, options)](#apidoc.element.grunt.file.minimatch.Minimatch)
- description and source-code
```javascript
function Minimatch(pattern, options) {
  if (!(this instanceof Minimatch)) {
    return new Minimatch(pattern, options)
  }

  if (typeof pattern !== 'string') {
    throw new TypeError('glob pattern string required')
  }

  if (!options) options = {}
  pattern = pattern.trim()

  // windows support: need to use /, not \
  if (path.sep !== '/') {
    pattern = pattern.split(path.sep).join('/')
  }

  this.options = options
  this.set = []
  this.pattern = pattern
  this.regexp = null
  this.negate = false
  this.comment = false
  this.empty = false

  // make the set of regexps etc.
  this.make()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.braceExpand"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>braceExpand (pattern, options)](#apidoc.element.grunt.file.minimatch.braceExpand)
- description and source-code
```javascript
braceExpand = function (pattern, options) {
  return braceExpand(pattern, options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.defaults"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>defaults (def)](#apidoc.element.grunt.file.minimatch.defaults)
- description and source-code
```javascript
defaults = function (def) {
  if (!def || !Object.keys(def).length) return minimatch

  var orig = minimatch

  var m = function minimatch (p, pattern, options) {
    return orig.minimatch(p, pattern, ext(def, options))
  }

  m.Minimatch = function Minimatch (pattern, options) {
    return new orig.Minimatch(pattern, ext(def, options))
  }

  return m
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.filter"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>filter (pattern, options)](#apidoc.element.grunt.file.minimatch.filter)
- description and source-code
```javascript
function filter(pattern, options) {
  options = options || {}
  return function (p, i, list) {
    return minimatch(p, pattern, options)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.makeRe"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>makeRe (pattern, options)](#apidoc.element.grunt.file.minimatch.makeRe)
- description and source-code
```javascript
makeRe = function (pattern, options) {
  return new Minimatch(pattern, options || {}).makeRe()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.match"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.</span>match (list, pattern, options)](#apidoc.element.grunt.file.minimatch.match)
- description and source-code
```javascript
match = function (list, pattern, options) {
  options = options || {}
  var mm = new Minimatch(pattern, options)
  list = list.filter(function (f) {
    return mm.match(f)
  })
  if (mm.options.nonull && !list.length) {
    list.push(pattern)
  }
  return list
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.file.minimatch.Minimatch.prototype"></a>[module grunt.file.minimatch.Minimatch.prototype](#apidoc.module.grunt.file.minimatch.Minimatch.prototype)

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch.prototype.braceExpand"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>braceExpand (pattern, options)](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.braceExpand)
- description and source-code
```javascript
function braceExpand(pattern, options) {
  if (!options) {
    if (this instanceof Minimatch) {
      options = this.options
    } else {
      options = {}
    }
  }

  pattern = typeof pattern === 'undefined'
    ? this.pattern : pattern

  if (typeof pattern === 'undefined') {
    throw new TypeError('undefined pattern')
  }

  if (options.nobrace ||
    !pattern.match(/\{.*\}/)) {
    // shortcut. no need to expand.
    return [pattern]
  }

  return expand(pattern)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch.prototype.debug"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>debug ()](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.debug)
- description and source-code
```javascript
debug = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch.prototype.make"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>make ()](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.make)
- description and source-code
```javascript
function make() {
  // don't do it more than once.
  if (this._made) return

  var pattern = this.pattern
  var options = this.options

  // empty patterns and comments match nothing.
  if (!options.nocomment && pattern.charAt(0) === '#') {
    this.comment = true
    return
  }
  if (!pattern) {
    this.empty = true
    return
  }

  // step 1: figure out negation, etc.
  this.parseNegate()

  // step 2: expand braces
  var set = this.globSet = this.braceExpand()

  if (options.debug) this.debug = console.error

  this.debug(this.pattern, set)

  // step 3: now we have a set, so turn each one into a series of path-portion
  // matching patterns.
  // These will be regexps, except in the case of "**", which is
  // set to the GLOBSTAR object for globstar behavior,
  // and will not contain any / characters
  set = this.globParts = set.map(function (s) {
    return s.split(slashSplit)
  })

  this.debug(this.pattern, set)

  // glob --> regexps
  set = set.map(function (s, si, set) {
    return s.map(this.parse, this)
  }, this)

  this.debug(this.pattern, set)

  // filter out everything that didn't compile properly.
  set = set.filter(function (s) {
    return s.indexOf(false) === -1
  })

  this.debug(this.pattern, set)

  this.set = set
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch.prototype.makeRe"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>makeRe ()](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.makeRe)
- description and source-code
```javascript
function makeRe() {
  if (this.regexp || this.regexp === false) return this.regexp

  // at this point, this.set is a 2d array of partial
  // pattern strings, or "**".
  //
  // It's better to use .match().  This function shouldn't
  // be used, really, but it's pretty convenient sometimes,
  // when you just want to work with a regex.
  var set = this.set

  if (!set.length) {
    this.regexp = false
    return this.regexp
  }
  var options = this.options

  var twoStar = options.noglobstar ? star
    : options.dot ? twoStarDot
    : twoStarNoDot
  var flags = options.nocase ? 'i' : ''

  var re = set.map(function (pattern) {
    return pattern.map(function (p) {
      return (p === GLOBSTAR) ? twoStar
      : (typeof p === 'string') ? regExpEscape(p)
      : p._src
    }).join('\\\/')
  }).join('|')

  // must match entire pattern
  // ending in a * or ** will make it less strict.
  re = '^(?:' + re + ')$'

  // can match anything, as long as it's not this.
  if (this.negate) re = '^(?!' + re + ').*$'

  try {
    this.regexp = new RegExp(re, flags)
  } catch (ex) {
    this.regexp = false
  }
  return this.regexp
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch.prototype.match"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>match (f, partial)](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.match)
- description and source-code
```javascript
function match(f, partial) {
  this.debug('match', f, this.pattern)
  // short-circuit in the case of busted things.
  // comments, etc.
  if (this.comment) return false
  if (this.empty) return f === ''

  if (f === '/' && partial) return true

  var options = this.options

  // windows: need to use /, not \
  if (path.sep !== '/') {
    f = f.split(path.sep).join('/')
  }

  // treat the test path as a set of pathparts.
  f = f.split(slashSplit)
  this.debug(this.pattern, 'split', f)

  // just ONE of the pattern sets in this.set needs to match
  // in order for it to be valid.  If negating, then just one
  // match means that we have failed.
  // Either way, return on the first hit.

  var set = this.set
  this.debug(this.pattern, 'set', set)

  // Find the basename of the path by looking for the last non-empty segment
  var filename
  var i
  for (i = f.length - 1; i >= 0; i--) {
    filename = f[i]
    if (filename) break
  }

  for (i = 0; i < set.length; i++) {
    var pattern = set[i]
    var file = f
    if (options.matchBase && pattern.length === 1) {
      file = [filename]
    }
    var hit = this.matchOne(file, pattern, partial)
    if (hit) {
      if (options.flipNegate) return true
      return !this.negate
    }
  }

  // didn't get any hits.  this is success if it's a negative
  // pattern, failure otherwise.
  if (options.flipNegate) return false
  return this.negate
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch.prototype.matchOne"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>matchOne (file, pattern, partial)](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.matchOne)
- description and source-code
```javascript
matchOne = function (file, pattern, partial) {
  var options = this.options

  this.debug('matchOne',
    { 'this': this, file: file, pattern: pattern })

  this.debug('matchOne', file.length, pattern.length)

  for (var fi = 0,
      pi = 0,
      fl = file.length,
      pl = pattern.length
      ; (fi < fl) && (pi < pl)
      ; fi++, pi++) {
    this.debug('matchOne loop')
    var p = pattern[pi]
    var f = file[fi]

    this.debug(pattern, p, f)

    // should be impossible.
    // some invalid regexp stuff in the set.
    if (p === false) return false

    if (p === GLOBSTAR) {
      this.debug('GLOBSTAR', [pattern, p, f])

      // "**"
      // a/**/b/**/c would match the following:
      // a/b/x/y/z/c
      // a/x/y/z/b/c
      // a/b/x/b/x/c
      // a/b/c
      // To do this, take the rest of the pattern after
      // the **, and see if it would match the file remainder.
      // If so, return success.
      // If not, the ** "swallows" a segment, and try again.
      // This is recursively awful.
      //
      // a/**/b/**/c matching a/b/x/y/z/c
      // - a matches a
      // - doublestar
      //   - matchOne(b/x/y/z/c, b/**/c)
      //     - b matches b
      //     - doublestar
      //       - matchOne(x/y/z/c, c) -> no
      //       - matchOne(y/z/c, c) -> no
      //       - matchOne(z/c, c) -> no
      //       - matchOne(c, c) yes, hit
      var fr = fi
      var pr = pi + 1
      if (pr === pl) {
        this.debug('** at the end')
        // a ** at the end will just swallow the rest.
        // We have found a match.
        // however, it will not swallow /.x, unless
        // options.dot is set.
        // . and .. are *never* matched by **, for explosively
        // exponential reasons.
        for (; fi < fl; fi++) {
          if (file[fi] === '.' || file[fi] === '..' ||
            (!options.dot && file[fi].charAt(0) === '.')) return false
        }
        return true
      }

      // ok, let's see if we can swallow whatever we can.
      while (fr < fl) {
        var swallowee = file[fr]

        this.debug('\nglobstar while', file, fr, pattern, pr, swallowee)

        // XXX remove this slice.  Just pass the start index.
        if (this.matchOne(file.slice(fr), pattern.slice(pr), partial)) {
          this.debug('globstar found match!', fr, fl, swallowee)
          // found a match.
          return true
        } else {
          // can't swallow "." or ".." ever.
          // can only swallow ".foo" when explicitly asked.
          if (swallowee === '.' || swallowee === '..' ||
            (!options.dot && swallowee.charAt(0) === '.')) {
            this.debug('dot detected!', file, fr, pattern, pr)
            break
          }

          // ** swallows a segment, and continue.
          this.debug('globstar swallow a segment, and continue')
          fr++
        }
      }

      // no match was found.
      // However, in partial mode, we can't say this is necessarily over.
      // If there's more *pattern* left, then
      if (partial) {
        // ran out of file
        this.debug('\n>>> no match, partial?', file, fr, pattern, pr)
        if (fr === fl) return true
      }
      return false
    }

    // something other than **
    // non-magic patterns just have to match exactly
    // patterns with magic have been turned into regexps.
    var hit
    if (typeof p === 'string') {
      if (options.nocase) {
        hit = f.toLowerCase() === p.toLowerCase()
      } else {
        hit = f === p
      }
      this.debug('string match', p, f, hit)
    } else {
      hit = f.match(p)
      this.debug('pattern match', p, f, hit)
    }

    if (!hit) return false
  }

  // Note: ending in / means that we'll get a final ""
  // at the end of the pattern.  This can only match a
  // corresponding "" at the end of the file.
  // If the file ends in /, then it can only match a
  // a pattern that ends in /, unless the pattern just
  // doesn't have any more for it. But, a/b/ should *not*
  // match "a/b/*", even though "" matches against the
  // [^/]*? pattern, except in partial mode, where i ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch.prototype.parse"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>parse (pattern, isSub)](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.parse)
- description and source-code
```javascript
function parse(pattern, isSub) {
  if (pattern.length > 1024 * 64) {
    throw new TypeError('pattern is too long')
  }

  var options = this.options

  // shortcuts
  if (!options.noglobstar && pattern === '**') return GLOBSTAR
  if (pattern === '') return ''

  var re = ''
  var hasMagic = !!options.nocase
  var escaping = false
  // ? => one single character
  var patternListStack = []
  var negativeLists = []
  var stateChar
  var inClass = false
  var reClassStart = -1
  var classStart = -1
  // . and .. never match anything that doesn't start with .,
  // even when options.dot is set.
  var patternStart = pattern.charAt(0) === '.' ? '' // anything
  // not (start or / followed by . or .. followed by / or end)
  : options.dot ? '(?!(?:^|\\\/)\\.{1,2}(?:$|\\\/))'
  : '(?!\\.)'
  var self = this

  function clearStateChar () {
    if (stateChar) {
      // we had some state-tracking character
      // that wasn't consumed by this pass.
      switch (stateChar) {
        case '*':
          re += star
          hasMagic = true
        break
        case '?':
          re += qmark
          hasMagic = true
        break
        default:
          re += '\\' + stateChar
        break
      }
      self.debug('clearStateChar %j %j', stateChar, re)
      stateChar = false
    }
  }

  for (var i = 0, len = pattern.length, c
    ; (i < len) && (c = pattern.charAt(i))
    ; i++) {
    this.debug('%s\t%s %s %j', pattern, i, re, c)

    // skip over any that are escaped.
    if (escaping && reSpecials[c]) {
      re += '\\' + c
      escaping = false
      continue
    }

    switch (c) {
      case '/':
        // completely not allowed, even escaped.
        // Should already be path-split by now.
        return false

      case '\\':
        clearStateChar()
        escaping = true
      continue

      // the various stateChar values
      // for the "extglob" stuff.
      case '?':
      case '*':
      case '+':
      case '@':
      case '!':
        this.debug('%s\t%s %s %j <-- stateChar', pattern, i, re, c)

        // all of those are literals inside a class, except that
        // the glob [!a] means [^a] in regexp
        if (inClass) {
          this.debug('  in class')
          if (c === '!' && i === classStart + 1) c = '^'
          re += c
          continue
        }

        // if we already have a stateChar, then it means
        // that there was something like ** or +? in there.
        // Handle the stateChar, then proceed with this one.
        self.debug('call clearStateChar %j', stateChar)
        clearStateChar()
        stateChar = c
        // if extglob is disabled, then +(asdf|foo) isn't a thing.
        // just clear the statechar *now*, rather than even diving into
        // the patternList stuff.
        if (options.noext) clearStateChar()
      continue

      case '(':
        if (inClass) {
          re += '('
          continue
        }

        if (!stateChar) {
          re += '\\('
          continue
        }

        patternListStack.push({
          type: stateChar,
          start: i - 1,
          reStart: re.length,
          open: plTypes[stateChar].open,
          close: plTypes[stateChar].close
        })
        // negation is (?:(?!js)[^/]*)
        re += stateChar === '!' ? '(?:(?!(?:' : '(?:'
        this.debug('plType %j %j', stateChar, re)
        stateChar = false
      continue

      case ')':
        if (inClass || !patternListStack.length) {
          re += '\\)'
          continue
        }

        clearStateChar()
        hasMagic = true
        var pl = patternListStack.pop()
        // negation is (?:(?!js)[^/]*)
        // The others are (?:<pattern>)<type>
        re += pl.close
        if (pl.type === '!') {
          negativeLists.push(pl)
        }
        pl.reEnd = re.length
      continue

      case '|':
        if (inClass || !patternListStack.length || escaping) {
          re += '\\|'
          escaping = false
          continue
        }

        clearStateChar()
        re += '|'
      continue

      // these are mostly the same in regexp and ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.file.minimatch.Minimatch.prototype.parseNegate"></a>[function <span class="apidocSignatureSpan">grunt.file.minimatch.Minimatch.prototype.</span>parseNegate ()](#apidoc.element.grunt.file.minimatch.Minimatch.prototype.parseNegate)
- description and source-code
```javascript
function parseNegate() {
  var pattern = this.pattern
  var negate = false
  var options = this.options
  var negateOffset = 0

  if (options.nonegate) return

  for (var i = 0, l = pattern.length
    ; i < l && pattern.charAt(i) === '!'
    ; i++) {
    negate = !negate
    negateOffset++
  }

  if (negateOffset) this.pattern = pattern.substr(negateOffset)
  this.negate = negate
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.help"></a>[module grunt.help](#apidoc.module.grunt.help)

#### <a name="apidoc.element.grunt.help.display"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>display ()](#apidoc.element.grunt.help.display)
- description and source-code
```javascript
display = function () {
  exports.queue.forEach(function(name) { exports[name](); });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.footer"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>footer ()](#apidoc.element.grunt.help.footer)
- description and source-code
```javascript
footer = function () {
  grunt.log.writeln().writeln('For more information, see http://gruntjs.com/');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.header"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>header ()](#apidoc.element.grunt.help.header)
- description and source-code
```javascript
header = function () {
  grunt.log.writeln('Grunt: The JavaScript Task Runner (v' + grunt.version + ')');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.initCol1"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>initCol1 (str)](#apidoc.element.grunt.help.initCol1)
- description and source-code
```javascript
initCol1 = function (str) {
  col1len = Math.max(col1len, str.length);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.initOptions"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>initOptions ()](#apidoc.element.grunt.help.initOptions)
- description and source-code
```javascript
initOptions = function () {
  // Build 2-column array for table view.
  exports._options = Object.keys(grunt.cli.optlist).map(function(long) {
    var o = grunt.cli.optlist[long];
    var col1 = '--' + (o.negate ? 'no-' : '') + long + (o.short ? ', -' + o.short : '');
    exports.initCol1(col1);
    return [col1, o.info];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.initTasks"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>initTasks ()](#apidoc.element.grunt.help.initTasks)
- description and source-code
```javascript
initTasks = function () {
  // Initialize task system so that the tasks can be listed.
  grunt.task.init([], {help: true});

  // Build object of tasks by info (where they were loaded from).
  exports._tasks = [];
  Object.keys(grunt.task._tasks).forEach(function(name) {
    exports.initCol1(name);
    var task = grunt.task._tasks[name];
    exports._tasks.push(task);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.initWidths"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>initWidths ()](#apidoc.element.grunt.help.initWidths)
- description and source-code
```javascript
initWidths = function () {
  // Widths for options/tasks table output.
  exports.widths = [1, col1len, 2, 76 - col1len];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.options"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>options ()](#apidoc.element.grunt.help.options)
- description and source-code
```javascript
options = function () {
  grunt.log.header('Options');
  exports.table(exports._options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.optionsFooter"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>optionsFooter ()](#apidoc.element.grunt.help.optionsFooter)
- description and source-code
```javascript
optionsFooter = function () {
  grunt.log.writeln().writelns(
    'Options marked with * have methods exposed via the grunt API and should ' +
    'instead be specified inside the Gruntfile wherever possible.'
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.table"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>table (arr)](#apidoc.element.grunt.help.table)
- description and source-code
```javascript
table = function (arr) {
  arr.forEach(function(item) {
    grunt.log.writetableln(exports.widths, ['', grunt.util._.pad(item[0], col1len), '', item[1]]);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.tasks"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>tasks ()](#apidoc.element.grunt.help.tasks)
- description and source-code
```javascript
tasks = function () {
  grunt.log.header('Available tasks');
  if (exports._tasks.length === 0) {
    grunt.log.writeln('(no tasks found)');
  } else {
    exports.table(exports._tasks.map(function(task) {
      var info = task.info;
      if (task.multi) { info += ' *'; }
      return [task.name, info];
    }));

    grunt.log.writeln().writelns(
      'Tasks run in the order specified. Arguments may be passed to tasks that ' +
      'accept them by using colons, like "lint:files". Tasks marked with * are ' +
      '"multi tasks" and will iterate over all sub-targets if no argument is ' +
      'specified.'
    );
  }

  grunt.log.writeln().writelns(
    'The list of available tasks may change based on tasks directories or ' +
    'grunt plugins specified in the Gruntfile or via command-line options.'
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.help.usage"></a>[function <span class="apidocSignatureSpan">grunt.help.</span>usage ()](#apidoc.element.grunt.help.usage)
- description and source-code
```javascript
usage = function () {
  grunt.log.header('Usage');
  grunt.log.writeln(' ' + path.basename(process.argv[1]) + ' [options] [task [task ...]]');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.log"></a>[module grunt.log](#apidoc.module.grunt.log)

#### <a name="apidoc.element.grunt.log._format"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>_format ()](#apidoc.element.grunt.log._format)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log._markup"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>_markup ()](#apidoc.element.grunt.log._markup)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log._write"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>_write ()](#apidoc.element.grunt.log._write)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log._writeln"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>_writeln ()](#apidoc.element.grunt.log._writeln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.debug"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>debug ()](#apidoc.element.grunt.log.debug)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.error"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>error ()](#apidoc.element.grunt.log.error)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.errorlns"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>errorlns ()](#apidoc.element.grunt.log.errorlns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.fail"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>fail ()](#apidoc.element.grunt.log.fail)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.header"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>header ()](#apidoc.element.grunt.log.header)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.initColors"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>initColors ()](#apidoc.element.grunt.log.initColors)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.ok"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>ok ()](#apidoc.element.grunt.log.ok)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.oklns"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>oklns ()](#apidoc.element.grunt.log.oklns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.option"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>option ()](#apidoc.element.grunt.log.option)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.subhead"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>subhead ()](#apidoc.element.grunt.log.subhead)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.success"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>success ()](#apidoc.element.grunt.log.success)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.table"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>table ()](#apidoc.element.grunt.log.table)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.uncolor"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>uncolor ()](#apidoc.element.grunt.log.uncolor)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.warn"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>warn ()](#apidoc.element.grunt.log.warn)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.wordlist"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>wordlist ()](#apidoc.element.grunt.log.wordlist)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.wraptext"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>wraptext ()](#apidoc.element.grunt.log.wraptext)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.write"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>write ()](#apidoc.element.grunt.log.write)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.writeflags"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>writeflags ()](#apidoc.element.grunt.log.writeflags)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.writeln"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>writeln ()](#apidoc.element.grunt.log.writeln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.writelns"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>writelns ()](#apidoc.element.grunt.log.writelns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.writetableln"></a>[function <span class="apidocSignatureSpan">grunt.log.</span>writetableln ()](#apidoc.element.grunt.log.writetableln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.log.notverbose"></a>[module grunt.log.notverbose](#apidoc.module.grunt.log.notverbose)

#### <a name="apidoc.element.grunt.log.notverbose._format"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_format ()](#apidoc.element.grunt.log.notverbose._format)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose._markup"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_markup ()](#apidoc.element.grunt.log.notverbose._markup)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose._write"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_write ()](#apidoc.element.grunt.log.notverbose._write)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose._writeln"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>_writeln ()](#apidoc.element.grunt.log.notverbose._writeln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.debug"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>debug ()](#apidoc.element.grunt.log.notverbose.debug)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.error"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>error ()](#apidoc.element.grunt.log.notverbose.error)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.errorlns"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>errorlns ()](#apidoc.element.grunt.log.notverbose.errorlns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.fail"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>fail ()](#apidoc.element.grunt.log.notverbose.fail)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.header"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>header ()](#apidoc.element.grunt.log.notverbose.header)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.initColors"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>initColors ()](#apidoc.element.grunt.log.notverbose.initColors)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.ok"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>ok ()](#apidoc.element.grunt.log.notverbose.ok)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.oklns"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>oklns ()](#apidoc.element.grunt.log.notverbose.oklns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.option"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>option ()](#apidoc.element.grunt.log.notverbose.option)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.subhead"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>subhead ()](#apidoc.element.grunt.log.notverbose.subhead)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.success"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>success ()](#apidoc.element.grunt.log.notverbose.success)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.table"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>table ()](#apidoc.element.grunt.log.notverbose.table)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.uncolor"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>uncolor ()](#apidoc.element.grunt.log.notverbose.uncolor)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.warn"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>warn ()](#apidoc.element.grunt.log.notverbose.warn)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.wordlist"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>wordlist ()](#apidoc.element.grunt.log.notverbose.wordlist)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.wraptext"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>wraptext ()](#apidoc.element.grunt.log.notverbose.wraptext)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.write"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>write ()](#apidoc.element.grunt.log.notverbose.write)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.writeflags"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>writeflags ()](#apidoc.element.grunt.log.notverbose.writeflags)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.writeln"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>writeln ()](#apidoc.element.grunt.log.notverbose.writeln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.writelns"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>writelns ()](#apidoc.element.grunt.log.notverbose.writelns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.log.notverbose.writetableln"></a>[function <span class="apidocSignatureSpan">grunt.log.notverbose.</span>writetableln ()](#apidoc.element.grunt.log.notverbose.writetableln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.option"></a>[module grunt.option](#apidoc.module.grunt.option)

#### <a name="apidoc.element.grunt.option.option"></a>[function <span class="apidocSignatureSpan">grunt.</span>option (key, value)](#apidoc.element.grunt.option.option)
- description and source-code
```javascript
option = function (key, value) {
  var no = key.match(/^no-(.+)$/);
  if (arguments.length === 2) {
    return (data[key] = value);
  } else if (no) {
    return data[no[1]] === false;
  } else {
    return data[key];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.option.flags"></a>[function <span class="apidocSignatureSpan">grunt.option.</span>flags ()](#apidoc.element.grunt.option.flags)
- description and source-code
```javascript
flags = function () {
  return Object.keys(data).filter(function(key) {
    // Don't display empty arrays.
    return !(Array.isArray(data[key]) && data[key].length === 0);
  }).map(function(key) {
    var val = data[key];
    return '--' + (val === false ? 'no-' : '') + key +
      (typeof val === 'boolean' ? '' : '=' + val);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.option.init"></a>[function <span class="apidocSignatureSpan">grunt.option.</span>init (obj)](#apidoc.element.grunt.option.init)
- description and source-code
```javascript
init = function (obj) {
  return (data = obj || {});
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.task"></a>[module grunt.task](#apidoc.module.grunt.task)

#### <a name="apidoc.element.grunt.task.init"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>init (tasks, options)](#apidoc.element.grunt.task.init)
- description and source-code
```javascript
init = function (tasks, options) {
  if (!options) { options = {}; }

  // Were only init tasks specified?
  var allInit = tasks.length > 0 && tasks.every(function(name) {
    var obj = task._taskPlusArgs(name).task;
    return obj && obj.init;
  });

  // Get any local Gruntfile or tasks that might exist. Use --gruntfile override
  // if specified, otherwise search the current directory or any parent.
  var gruntfile, msg;
  if (allInit || options.gruntfile === false) {
    gruntfile = null;
  } else {
    gruntfile = grunt.option('gruntfile') ||
      grunt.file.findup('Gruntfile.{js,coffee}', {nocase: true});
    msg = 'Reading "' + (gruntfile ? path.basename(gruntfile) : '???') + '" Gruntfile...';
  }

  if (options.gruntfile === false) {
    // Grunt was run as a lib with {gruntfile: false}.
  } else if (gruntfile && grunt.file.exists(gruntfile)) {
    grunt.verbose.writeln().write(msg).ok();
    // Change working directory so that all paths are relative to the
    // Gruntfile's location (or the --base option, if specified).
    process.chdir(grunt.option('base') || path.dirname(gruntfile));
    // Load local tasks, if the file exists.
    loadTasksMessage('Gruntfile');
    loadTask(gruntfile);
  } else if (options.help || allInit) {
    // Don't complain about missing Gruntfile.
  } else if (grunt.option('gruntfile')) {
    // If --config override was specified and it doesn't exist, complain.
    grunt.log.writeln().write(msg).error();
    grunt.fatal('Unable to find "' + gruntfile + '" Gruntfile.', grunt.fail.code.MISSING_GRUNTFILE);
  } else if (!grunt.option('help')) {
    grunt.verbose.writeln().write(msg).error();
    grunt.log.writelns(
      'A valid Gruntfile could not be found. Please see the getting ' +
      'started guide for more information on how to configure grunt: ' +
      'http://gruntjs.com/getting-started'
    );
    grunt.fatal('Unable to find Gruntfile.', grunt.fail.code.MISSING_GRUNTFILE);
  }

  // Load all user-specified --npm tasks.
  (grunt.option('npm') || []).map(String).forEach(task.loadNpmTasks);
  // Load all user-specified --tasks.
  (grunt.option('tasks') || []).map(String).forEach(task.loadTasks);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.task.loadNpmTasks"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>loadNpmTasks (name)](#apidoc.element.grunt.task.loadNpmTasks)
- description and source-code
```javascript
loadNpmTasks = function (name) {
  loadTasksMessage('"' + name + '" local Npm module');
  var root = path.resolve('node_modules');
  var pkgfile = path.join(root, name, 'package.json');
  var pkg = grunt.file.exists(pkgfile) ? grunt.file.readJSON(pkgfile) : {keywords: []};

  // Process collection plugins.
  if (pkg.keywords && pkg.keywords.indexOf('gruntcollection') !== -1) {
    loadTaskDepth++;
    Object.keys(pkg.dependencies).forEach(function(depName) {
      // Npm sometimes pulls dependencies out if they're shared, so find
      // upwards if not found locally.
      var filepath = grunt.file.findup('node_modules/' + depName, {
        cwd: path.resolve('node_modules', name),
        nocase: true
      });
      if (filepath) {
        // Load this task plugin recursively.
        task.loadNpmTasks(path.relative(root, filepath));
      }
    });
    loadTaskDepth--;
    return;
  }

  // Process task plugins.
  var tasksdir = path.join(root, name, 'tasks');
  if (grunt.file.exists(tasksdir)) {
    loadTasks(tasksdir);
  } else {
    grunt.log.error('Local Npm module "' + name + '" not found. Is it installed?');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.task.loadTasks"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>loadTasks (tasksdir)](#apidoc.element.grunt.task.loadTasks)
- description and source-code
```javascript
loadTasks = function (tasksdir) {
  loadTasksMessage('"' + tasksdir + '"');
  if (grunt.file.exists(tasksdir)) {
    loadTasks(tasksdir);
  } else {
    grunt.log.error('Tasks directory "' + tasksdir + '" not found.');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.task.normalizeMultiTaskFiles"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>normalizeMultiTaskFiles (data, target)](#apidoc.element.grunt.task.normalizeMultiTaskFiles)
- description and source-code
```javascript
normalizeMultiTaskFiles = function (data, target) {
  var prop, obj;
  var files = [];
  if (grunt.util.kindOf(data) === 'object') {
    if ('src' in data || 'dest' in data) {
      obj = {};
      for (prop in data) {
        if (prop !== 'options') {
          obj[prop] = data[prop];
        }
      }
      files.push(obj);
    } else if (grunt.util.kindOf(data.files) === 'object') {
      for (prop in data.files) {
        files.push({src: data.files[prop], dest: grunt.config.process(prop)});
      }
    } else if (Array.isArray(data.files)) {
      grunt.util._.flattenDeep(data.files).forEach(function(obj) {
        var prop;
        if ('src' in obj || 'dest' in obj) {
          files.push(obj);
        } else {
          for (prop in obj) {
            files.push({src: obj[prop], dest: grunt.config.process(prop)});
          }
        }
      });
    }
  } else {
    files.push({src: data, dest: grunt.config.process(target)});
  }

  // If no src/dest or files were specified, return an empty files array.
  if (files.length === 0) {
    grunt.verbose.writeln('File: ' + '[no files]'.yellow);
    return [];
  }

  // Process all normalized file objects.
  files = grunt.util._(files).chain().forEach(function(obj) {
    if (!('src' in obj) || !obj.src) { return; }
    // Normalize .src properties to flattened array.
    if (Array.isArray(obj.src)) {
      obj.src = grunt.util._.flatten(obj.src);
    } else {
      obj.src = [obj.src];
    }
  }).map(function(obj) {
    // Build options object, removing unwanted properties.
    var expandOptions = grunt.util._.extend({}, obj);
    delete expandOptions.src;
    delete expandOptions.dest;

    // Expand file mappings.
    if (obj.expand) {
      return grunt.file.expandMapping(obj.src, obj.dest, expandOptions).map(function(mapObj) {
        // Copy obj properties to result.
        var result = grunt.util._.extend({}, obj);
        // Make a clone of the orig obj available.
        result.orig = grunt.util._.extend({}, obj);
        // Set .src and .dest, processing both as templates.
        result.src = grunt.config.process(mapObj.src);
        result.dest = grunt.config.process(mapObj.dest);
        // Remove unwanted properties.
        ['expand', 'cwd', 'flatten', 'rename', 'ext'].forEach(function(prop) {
          delete result[prop];
        });
        return result;
      });
    }

    // Copy obj properties to result, adding an .orig property.
    var result = grunt.util._.extend({}, obj);
    // Make a clone of the orig obj available.
    result.orig = grunt.util._.extend({}, obj);

    if ('src' in result) {
      // Expose an expand-on-demand getter method as .src.
      Object.defineProperty(result, 'src', {
        enumerable: true,
        get: function fn() {
          var src;
          if (!('result' in fn)) {
            src = obj.src;
            // If src is an array, flatten it. Otherwise, make it into an array.
            src = Array.isArray(src) ? grunt.util._.flatten(src) : [src];
            // Expand src files, memoizing result.
            fn.result = grunt.file.expand(expandOptions, src);
          }
          return fn.result;
        }
      });
    }

    if ('dest' in result) {
      result.dest = obj.dest;
    }

    return result;
  }).flatten().value();

  // Log this.file src and dest properties when --verbose is specified.
  if (grunt.option('verbose')) {
    files.forEach(function(obj) {
      var output = [];
      if ('src' in obj) {
        output.push(obj.src.length > 0 ? grunt.log.wordlist(obj.src) : '[no src]'.yellow);
      }
      if ('dest' in obj) {
        output.push('-> ' + (obj.dest ? String(obj.dest).cyan : '[no dest]'.yellow));
      }
      if (output.length > 0) {
        grunt.verbose.writeln('Files: ' + output.join(' '));
      }
    });
  }

  return files;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.task.registerInitTask"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>registerInitTask (name, info, fn)](#apidoc.element.grunt.task.registerInitTask)
- description and source-code
```javascript
registerInitTask = function (name, info, fn) {
  task.registerTask(name, info, fn);
  task._tasks[name].init = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.task.registerMultiTask"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>registerMultiTask (name, info, fn)](#apidoc.element.grunt.task.registerMultiTask)
- description and source-code
```javascript
registerMultiTask = function (name, info, fn) {
  // If optional "info" string is omitted, shuffle arguments a bit.
  if (fn == null) {
    fn = info;
    info = 'Custom multi task.';
  }
  // Store a reference to the task object, in case the task gets renamed.
  var thisTask;
  task.registerTask(name, info, function(target) {
    // Guaranteed to always be the actual task name.
    var name = thisTask.name;
    // Arguments (sans target) as an array.
    this.args = grunt.util.toArray(arguments).slice(1);
    // If a target wasn't specified, run this task once for each target.
    if (!target || target === '*') {
      return task.runAllTargets(name, this.args);
    } else if (!isValidMultiTaskTarget(target)) {
      throw new Error('Invalid target "' + target + '" specified.');
    }
    // Fail if any required config properties have been omitted.
    this.requiresConfig([name, target]);
    // Return an options object with the specified defaults overwritten by task-
    // and/or target-specific overrides, via the "options" property.
    this.options = function() {
      var targetObj = grunt.config([name, target]);
      var args = [{}].concat(grunt.util.toArray(arguments)).concat([
        grunt.config([name, 'options']),
        grunt.util.kindOf(targetObj) === 'object' ? targetObj.options : {}
      ]);
      var options = grunt.util._.extend.apply(null, args);
      grunt.verbose.writeflags(options, 'Options');
      return options;
    };
    // Expose the current target.
    this.target = target;
    // Recreate flags object so that the target isn't set as a flag.
    this.flags = {};
    this.args.forEach(function(arg) { this.flags[arg] = true; }, this);
    // Expose data on 'this' (as well as task.current).
    this.data = grunt.config([name, target]);
    // Expose normalized files object.
    this.files = task.normalizeMultiTaskFiles(this.data, target);
    // Expose normalized, flattened, uniqued array of src files.
    Object.defineProperty(this, 'filesSrc', {
      enumerable: true,
      get: function() {
        return grunt.util._(this.files).chain().map('src').flatten().uniq().value();
      }.bind(this)
    });
    // Call original task function, passing in the target and any other args.
    return fn.apply(this, this.args);
  });

  thisTask = task._tasks[name];
  thisTask.multi = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.task.registerTask"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>registerTask (name)](#apidoc.element.grunt.task.registerTask)
- description and source-code
```javascript
registerTask = function (name) {
  // Add task to registry.
  registry.tasks.push(name);
  // Register task.
  parent.registerTask.apply(task, arguments);
  // This task, now that it's been registered.
  var thisTask = task._tasks[name];
  // Metadata about the current task.
  thisTask.meta = grunt.util._.clone(registry.meta);
  // Override task function.
  var _fn = thisTask.fn;
  thisTask.fn = function(arg) {
    // Guaranteed to always be the actual task name.
    var name = thisTask.name;
    // Initialize the errorcount for this task.
    errorcount = grunt.fail.errorcount;
    // Return the number of errors logged during this task.
    Object.defineProperty(this, 'errorCount', {
      enumerable: true,
      get: function() {
        return grunt.fail.errorcount - errorcount;
      }
    });
    // Expose task.requires on 'this'.
    this.requires = task.requires.bind(task);
    // Expose config.requires on 'this'.
    this.requiresConfig = grunt.config.requires;
    // Return an options object with the specified defaults overwritten by task-
    // specific overrides, via the "options" property.
    this.options = function() {
      var args = [{}].concat(grunt.util.toArray(arguments)).concat([
        grunt.config([name, 'options'])
      ]);
      var options = grunt.util._.extend.apply(null, args);
      grunt.verbose.writeflags(options, 'Options');
      return options;
    };
    // If this task was an alias or a multi task called without a target,
    // only log if in verbose mode.
    var logger = _fn.alias || (thisTask.multi && (!arg || arg === '*')) ? 'verbose' : 'log';
    // Actually log.
    grunt[logger].header('Running "' + this.nameArgs + '"' +
      (this.name !== this.nameArgs ? ' (' + this.name + ')' : '') + ' task');
    // If --debug was specified, log the path to this task's source file.
    grunt[logger].debug('Task source: ' + thisTask.meta.filepath);
    // Actually run the task.
    return _fn.apply(this, arguments);
  };
  return task;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.task.renameTask"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>renameTask (oldname, newname)](#apidoc.element.grunt.task.renameTask)
- description and source-code
```javascript
renameTask = function (oldname, newname) {
  var result;
  try {
    // Actually rename task.
    result = parent.renameTask.apply(task, arguments);
    // Add and remove task.
    registry.untasks.push(oldname);
    registry.tasks.push(newname);
    // Return result.
    return result;
  } catch (e) {
    grunt.log.error(e.message);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.task.runAllTargets"></a>[function <span class="apidocSignatureSpan">grunt.task.</span>runAllTargets (taskname, args)](#apidoc.element.grunt.task.runAllTargets)
- description and source-code
```javascript
runAllTargets = function (taskname, args) {
  // Get an array of sub-property keys under the given config object.
  var targets = Object.keys(grunt.config.getRaw(taskname) || {});
  // Remove invalid target properties.
  targets = targets.filter(isValidMultiTaskTarget);
  // Fail if there are no actual properties to iterate over.
  if (targets.length === 0) {
    grunt.log.error('No "' + taskname + '" targets found.');
    return false;
  }
  // Iterate over all targets, running a task for each.
  targets.forEach(function(target) {
    // Be sure to pass in any additionally specified args.
    task.run([taskname, target].concat(args || []).join(':'));
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.template"></a>[module grunt.template](#apidoc.module.grunt.template)

#### <a name="apidoc.element.grunt.template.addDelimiters"></a>[function <span class="apidocSignatureSpan">grunt.template.</span>addDelimiters (name, opener, closer)](#apidoc.element.grunt.template.addDelimiters)
- description and source-code
```javascript
addDelimiters = function (name, opener, closer) {
  var delimiters = allDelimiters[name] = {};
  // Used by grunt.
  delimiters.opener = opener;
  delimiters.closer = closer;
  // Generate RegExp patterns dynamically.
  var a = delimiters.opener.replace(/(.)/g, '\\$1');
  var b = '([\\s\\S]+?)' + delimiters.closer.replace(/(.)/g, '\\$1');
  // Used by Lo-Dash.
  delimiters.lodash = {
    evaluate: new RegExp(a + b, 'g'),
    interpolate: new RegExp(a + '=' + b, 'g'),
    escape: new RegExp(a + '-' + b, 'g')
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.template.date"></a>[function <span class="apidocSignatureSpan">grunt.template.</span>date (date, mask, utc, gmt)](#apidoc.element.grunt.template.date)
- description and source-code
```javascript
date = function (date, mask, utc, gmt) {

      // You can't provide utc if you skip other args (use the 'UTC:' mask prefix)
      if (arguments.length === 1 && kindOf(date) === 'string' && !/\d/.test(date)) {
        mask = date;
        date = undefined;
      }

      date = date || new Date;

      if(!(date instanceof Date)) {
        date = new Date(date);
      }

      if (isNaN(date)) {
        throw TypeError('Invalid date');
      }

      mask = String(dateFormat.masks[mask] || mask || dateFormat.masks['default']);

      // Allow setting the utc/gmt argument via the mask
      var maskSlice = mask.slice(0, 4);
      if (maskSlice === 'UTC:' || maskSlice === 'GMT:') {
        mask = mask.slice(4);
        utc = true;
        if (maskSlice === 'GMT:') {
          gmt = true;
        }
      }

      var _ = utc ? 'getUTC' : 'get';
      var d = date[_ + 'Date']();
      var D = date[_ + 'Day']();
      var m = date[_ + 'Month']();
      var y = date[_ + 'FullYear']();
      var H = date[_ + 'Hours']();
      var M = date[_ + 'Minutes']();
      var s = date[_ + 'Seconds']();
      var L = date[_ + 'Milliseconds']();
      var o = utc ? 0 : date.getTimezoneOffset();
      var W = getWeek(date);
      var N = getDayOfWeek(date);
      var flags = {
        d:    d,
        dd:   pad(d),
        ddd:  dateFormat.i18n.dayNames[D],
        dddd: dateFormat.i18n.dayNames[D + 7],
        m:    m + 1,
        mm:   pad(m + 1),
        mmm:  dateFormat.i18n.monthNames[m],
        mmmm: dateFormat.i18n.monthNames[m + 12],
        yy:   String(y).slice(2),
        yyyy: y,
        h:    H % 12 || 12,
        hh:   pad(H % 12 || 12),
        H:    H,
        HH:   pad(H),
        M:    M,
        MM:   pad(M),
        s:    s,
        ss:   pad(s),
        l:    pad(L, 3),
        L:    pad(Math.round(L / 10)),
        t:    H < 12 ? 'a'  : 'p',
        tt:   H < 12 ? 'am' : 'pm',
        T:    H < 12 ? 'A'  : 'P',
        TT:   H < 12 ? 'AM' : 'PM',
        Z:    gmt ? 'GMT' : utc ? 'UTC' : (String(date).match(timezone) || ['']).pop().replace(timezoneClip, ''),
        o:    (o > 0 ? '-' : '+') + pad(Math.floor(Math.abs(o) / 60) * 100 + Math.abs(o) % 60, 4),
        S:    ['th', 'st', 'nd', 'rd'][d % 10 > 3 ? 0 : (d % 100 - d % 10 != 10) * d % 10],
        W:    W,
        N:    N
      };

      return mask.replace(token, function (match) {
        if (match in flags) {
          return flags[match];
        }
        return match.slice(1, match.length - 1);
      });
    }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.template.process"></a>[function <span class="apidocSignatureSpan">grunt.template.</span>process (tmpl, options)](#apidoc.element.grunt.template.process)
- description and source-code
```javascript
process = function (tmpl, options) {
  if (!options) { options = {}; }
  // Set delimiters, and get a opening match character.
  var delimiters = template.setDelimiters(options.delimiters);
  // Clone data, initializing to config data or empty object if omitted.
  var data = Object.create(options.data || grunt.config.data || {});
  // Expose grunt so that grunt utilities can be accessed, but only if it
  // doesn't conflict with an existing .grunt property.
  if (!('grunt' in data)) { data.grunt = grunt; }
  // Keep track of last change.
  var last = tmpl;
  try {
    // As long as tmpl contains template tags, render it and get the result,
    // otherwise just use the template string.
    while (tmpl.indexOf(delimiters.opener) >= 0) {
      tmpl = grunt.util._.template(tmpl, options)(data);
      // Abort if template didn't change - nothing left to process!
      if (tmpl === last) { break; }
      last = tmpl;
    }
  } catch (e) {
    // In upgrading to Lo-Dash (or Underscore.js 1.3.3), \n and \r in template
    // tags now causes an exception to be thrown. Warn the user why this is
    // happening. https://github.com/documentcloud/underscore/issues/553
    if (String(e) === 'SyntaxError: Unexpected token ILLEGAL' && /\n|\r/.test(tmpl)) {
      grunt.log.errorlns('A special character was detected in this template. ' +
        'Inside template tags, the \\n and \\r special characters must be ' +
        'escaped as \\\\n and \\\\r. (grunt 0.4.0+)');
    }
    // Slightly better error message.
    e.message = 'An error occurred while processing a template (' + e.message + ').';
    grunt.warn(e, grunt.fail.code.TEMPLATE_ERROR);
  }
  // Normalize linefeeds and return.
  return grunt.util.normalizelf(tmpl);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.template.setDelimiters"></a>[function <span class="apidocSignatureSpan">grunt.template.</span>setDelimiters (name)](#apidoc.element.grunt.template.setDelimiters)
- description and source-code
```javascript
setDelimiters = function (name) {
  // Get the appropriate delimiters.
  var delimiters = allDelimiters[name in allDelimiters ? name : 'config'];
  // Tell Lo-Dash which delimiters to use.
  grunt.util._.extend(grunt.util._.templateSettings, delimiters.lodash);
  // Return the delimiters.
  return delimiters;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.template.today"></a>[function <span class="apidocSignatureSpan">grunt.template.</span>today (format)](#apidoc.element.grunt.template.today)
- description and source-code
```javascript
today = function (format) {
  return template.date(new Date(), format);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util"></a>[module grunt.util](#apidoc.module.grunt.util)

#### <a name="apidoc.element.grunt.util.callbackify"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>callbackify (fn)](#apidoc.element.grunt.util.callbackify)
- description and source-code
```javascript
callbackify = function (fn) {
  return function callbackable() {
    // Invoke original function, getting its result.
    var result = fn.apply(this, arguments);
    // If the same number or less arguments were specified than fn accepts,
    // assume the "done" callback was already handled.
    var length = arguments.length;
    if (length === fn.length) { return; }
    // Otherwise, if the last argument is a function, assume it is a "done"
    // callback and call it.
    var done = arguments[length - 1];
    if (typeof done === 'function') { done(result); }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.error"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>error (err, origError)](#apidoc.element.grunt.util.error)
- description and source-code
```javascript
error = function (err, origError) {
  if (!nodeUtil.isError(err)) { err = new Error(err); }
  if (origError) { err.origError = origError; }
  return err;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.exit"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>exit (exitCode, streams)](#apidoc.element.grunt.util.exit)
- description and source-code
```javascript
function exit(exitCode, streams) {
  if (!streams) { streams = [process.stdout, process.stderr]; }
  var drainCount = 0;
  // Actually exit if all streams are drained.
  function tryToExit() {
    if (drainCount === streams.length) {
      process.exit(exitCode);
    }
  }
  streams.forEach(function(stream) {
    // Count drained streams now, but monitor non-drained streams.
    if (stream.bufferSize === 0) {
      drainCount++;
    } else {
      stream.write('', 'utf-8', function() {
        drainCount++;
        tryToExit();
      });
    }
    // Prevent further writing.
    stream.write = function() {};
  });
  // If all streams were already drained, exit now.
  tryToExit();
  // In Windows, when run as a Node.js child process, a script utilizing
  // this library might just exit with a 0 exit code, regardless. This code,
  // despite the fact that it looks a bit crazy, appears to fix that.
  process.on('exit', function() {
    process.exit(exitCode);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.kindOf"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>kindOf (value)](#apidoc.element.grunt.util.kindOf)
- description and source-code
```javascript
kindOf = function (value) {
  // Null or undefined.
  if (value == null) { return String(value); }
  // Everything else.
  return kindsOf[kindsOf.toString.call(value)] || 'object';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.normalizelf"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>normalizelf (str)](#apidoc.element.grunt.util.normalizelf)
- description and source-code
```javascript
normalizelf = function (str) {
  return str.replace(/\r\n|\n/g, util.linefeed);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.pluralize"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>pluralize (n, str, separator)](#apidoc.element.grunt.util.pluralize)
- description and source-code
```javascript
pluralize = function (n, str, separator) {
  var parts = str.split(separator || '/');
  return n === 1 ? (parts[0] || '') : (parts[1] || '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.recurse"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>recurse (value, fn, fnContinue)](#apidoc.element.grunt.util.recurse)
- description and source-code
```javascript
recurse = function (value, fn, fnContinue) {
  function recurse(value, fn, fnContinue, state) {
    var error;
    if (state.objs.indexOf(value) !== -1) {
      error = new Error('Circular reference detected (' + state.path + ')');
      error.path = state.path;
      throw error;
    }
    var obj, key;
    if (fnContinue && fnContinue(value) === false) {
      // Skip value if necessary.
      return value;
    } else if (util.kindOf(value) === 'array') {
      // If value is an array, recurse.
      return value.map(function(item, index) {
        return recurse(item, fn, fnContinue, {
          objs: state.objs.concat([value]),
          path: state.path + '[' + index + ']',
        });
      });
    } else if (util.kindOf(value) === 'object' && !Buffer.isBuffer(value)) {
      // If value is an object, recurse.
      obj = {};
      for (key in value) {
        obj[key] = recurse(value[key], fn, fnContinue, {
          objs: state.objs.concat([value]),
          path: state.path + (/\W/.test(key) ? '["' + key + '"]' : '.' + key),
        });
      }
      return obj;
    } else {
      // Otherwise pass value into fn and return.
      return fn(value);
    }
  }
  return recurse(value, fn, fnContinue, {objs: [], path: ''});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.repeat"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>repeat (n, str)](#apidoc.element.grunt.util.repeat)
- description and source-code
```javascript
repeat = function (n, str) {
  return new Array(n + 1).join(str || ' ');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.spawn"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>spawn (opts, done)](#apidoc.element.grunt.util.spawn)
- description and source-code
```javascript
spawn = function (opts, done) {
  // Build a result object and pass it (among other things) into the
  // done function.
  var callDone = function(code, stdout, stderr) {
    // Remove trailing whitespace (newline)
    stdout = _.rtrim(stdout);
    stderr = _.rtrim(stderr);
    // Create the result object.
    var result = {
      stdout: stdout,
      stderr: stderr,
      code: code,
      toString: function() {
        if (code === 0) {
          return stdout;
        } else if ('fallback' in opts) {
          return opts.fallback;
        } else if (opts.grunt) {
          // grunt.log.error uses standard out, to be fixed in 0.5.
          return stderr || stdout;
        }
        return stderr;
      }
    };
    // On error (and no fallback) pass an error object, otherwise pass null.
    done(code === 0 || 'fallback' in opts ? null : new Error(stderr), result, code);
  };

  var cmd, args;
  var pathSeparatorRe = /[\\\/]/g;
  if (opts.grunt) {
    cmd = process.execPath;
    args = process.execArgv.concat(process.argv[1], opts.args);
  } else {
    // On Windows, child_process.spawn will only file .exe files in the PATH,
    // not other executable types (grunt issue #155).
    try {
      if (!pathSeparatorRe.test(opts.cmd)) {
        // Only use which if cmd has no path component.
        cmd = which(opts.cmd);
      } else {
        cmd = opts.cmd.replace(pathSeparatorRe, path.sep);
      }
    } catch (err) {
      callDone(127, '', String(err));
      return;
    }
    args = opts.args || [];
  }

  var child = spawn(cmd, args, opts.opts);
  var stdout = new Buffer('');
  var stderr = new Buffer('');
  if (child.stdout) {
    child.stdout.on('data', function(buf) {
      stdout = Buffer.concat([stdout, new Buffer(buf)]);
    });
  }
  if (child.stderr) {
    child.stderr.on('data', function(buf) {
      stderr = Buffer.concat([stderr, new Buffer(buf)]);
    });
  }
  child.on('close', function(code) {
    callDone(code, stdout.toString(), stderr.toString());
  });
  return child;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.toArray"></a>[function <span class="apidocSignatureSpan">grunt.util.</span>toArray (value)](#apidoc.element.grunt.util.toArray)
- description and source-code
```javascript
function toArray(value) {
  if (!value) {
    return [];
  }
  if (isArrayLike(value)) {
    return isString(value) ? stringToArray(value) : copyArray(value);
  }
  if (iteratorSymbol && value[iteratorSymbol]) {
    return iteratorToArray(value[iteratorSymbol]());
  }
  var tag = getTag(value),
      func = tag == mapTag ? mapToArray : (tag == setTag ? setToArray : values);

  return func(value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util._"></a>[module grunt.util._](#apidoc.module.grunt.util._)

#### <a name="apidoc.element.grunt.util._.add"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>add (augend, addend)](#apidoc.element.grunt.util._.add)
- description and source-code
```javascript
function add(augend, addend) {
  var result;
  if (augend === undefined && addend === undefined) {
    return 0;
  }
  if (augend !== undefined) {
    result = augend;
  }
  if (addend !== undefined) {
    result = result === undefined ? addend : (result + addend);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.after"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>after (n, func)](#apidoc.element.grunt.util._.after)
- description and source-code
```javascript
function after(n, func) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  n = toInteger(n);
  return function() {
    if (--n < 1) {
      return func.apply(this, arguments);
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.ary"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>ary (func, n, guard)](#apidoc.element.grunt.util._.ary)
- description and source-code
```javascript
function ary(func, n, guard) {
  n = guard ? undefined : n;
  n = (func && n == null) ? func.length : n;
  return createWrapper(func, ARY_FLAG, undefined, undefined, undefined, undefined, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.assign"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>assign ()](#apidoc.element.grunt.util._.assign)
- description and source-code
```javascript
assign = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.assignIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>assignIn ()](#apidoc.element.grunt.util._.assignIn)
- description and source-code
```javascript
assignIn = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.assignInWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>assignInWith ()](#apidoc.element.grunt.util._.assignInWith)
- description and source-code
```javascript
assignInWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.assignWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>assignWith ()](#apidoc.element.grunt.util._.assignWith)
- description and source-code
```javascript
assignWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.at"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>at ()](#apidoc.element.grunt.util._.at)
- description and source-code
```javascript
at = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.attempt"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>attempt ()](#apidoc.element.grunt.util._.attempt)
- description and source-code
```javascript
attempt = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.before"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>before (n, func)](#apidoc.element.grunt.util._.before)
- description and source-code
```javascript
function before(n, func) {
  var result;
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  n = toInteger(n);
  return function() {
    if (--n > 0) {
      result = func.apply(this, arguments);
    }
    if (n <= 1) {
      func = undefined;
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.bind"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>bind ()](#apidoc.element.grunt.util._.bind)
- description and source-code
```javascript
bind = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.bindAll"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>bindAll ()](#apidoc.element.grunt.util._.bindAll)
- description and source-code
```javascript
bindAll = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.bindKey"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>bindKey ()](#apidoc.element.grunt.util._.bindKey)
- description and source-code
```javascript
bindKey = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.camelCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>camelCase (string)](#apidoc.element.grunt.util._.camelCase)
- description and source-code
```javascript
camelCase = function (string) {
  return arrayReduce(words(deburr(string)), callback, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.camelcase"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>camelcase (str, decapitalize)](#apidoc.element.grunt.util._.camelcase)
- description and source-code
```javascript
function camelize(str, decapitalize) {
  str = trim(str).replace(/[-_\s]+(.)?/g, function(match, c) {
    return c ? c.toUpperCase() : "";
  });

  if (decapitalize === true) {
    return decap(str);
  } else {
    return str;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.camelize"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>camelize (str, decapitalize)](#apidoc.element.grunt.util._.camelize)
- description and source-code
```javascript
function camelize(str, decapitalize) {
  str = trim(str).replace(/[-_\s]+(.)?/g, function(match, c) {
    return c ? c.toUpperCase() : "";
  });

  if (decapitalize === true) {
    return decap(str);
  } else {
    return str;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.capitalize"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>capitalize (str, lowercaseRest)](#apidoc.element.grunt.util._.capitalize)
- description and source-code
```javascript
function capitalize(str, lowercaseRest) {
  str = makeString(str);
  var remainingChars = !lowercaseRest ? str.slice(1) : str.slice(1).toLowerCase();

  return str.charAt(0).toUpperCase() + remainingChars;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.ceil"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>ceil (number, precision)](#apidoc.element.grunt.util._.ceil)
- description and source-code
```javascript
ceil = function (number, precision) {
  number = toNumber(number);
  precision = toInteger(precision);
  if (precision) {
    // Shift with exponential notation to avoid floating-point issues.
    // See [MDN](https://mdn.io/round#Examples) for more details.
    var pair = (toString(number) + 'e').split('e'),
        value = func(pair[0] + 'e' + (+pair[1] + precision));

    pair = (toString(value) + 'e').split('e');
    return +(pair[0] + 'e' + (+pair[1] - precision));
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.center"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>center (str, length, padStr)](#apidoc.element.grunt.util._.center)
- description and source-code
```javascript
function lrpad(str, length, padStr) {
  return pad(str, length, padStr, 'both');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.chain"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>chain (value)](#apidoc.element.grunt.util._.chain)
- description and source-code
```javascript
function chain(value) {
  var result = lodash(value);
  result.__chain__ = true;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.chars"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>chars (str)](#apidoc.element.grunt.util._.chars)
- description and source-code
```javascript
function chars(str) {
  return makeString(str).split('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.chop"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>chop (str, step)](#apidoc.element.grunt.util._.chop)
- description and source-code
```javascript
function chop(str, step) {
  if (str == null) return [];
  str = String(str);
  step = ~~step;
  return step > 0 ? str.match(new RegExp('.{1,' + step + '}', 'g')) : [str];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.chunk"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>chunk (array, size)](#apidoc.element.grunt.util._.chunk)
- description and source-code
```javascript
function chunk(array, size) {
  size = nativeMax(toInteger(size), 0);

  var length = array ? array.length : 0;
  if (!length || size < 1) {
    return [];
  }
  var index = 0,
      resIndex = -1,
      result = Array(nativeCeil(length / size));

  while (index < length) {
    result[++resIndex] = baseSlice(array, index, (index += size));
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.clamp"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>clamp (number, lower, upper)](#apidoc.element.grunt.util._.clamp)
- description and source-code
```javascript
function clamp(number, lower, upper) {
  if (upper === undefined) {
    upper = lower;
    lower = undefined;
  }
  if (upper !== undefined) {
    upper = toNumber(upper);
    upper = upper === upper ? upper : 0;
  }
  if (lower !== undefined) {
    lower = toNumber(lower);
    lower = lower === lower ? lower : 0;
  }
  return baseClamp(toNumber(number), lower, upper);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.classify"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>classify (str)](#apidoc.element.grunt.util._.classify)
- description and source-code
```javascript
function classify(str) {
  str = makeString(str);
  return capitalize(camelize(str.replace(/[\W_]/g, ' ')).replace(/\s/g, ''));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.clean"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>clean (str)](#apidoc.element.grunt.util._.clean)
- description and source-code
```javascript
function clean(str) {
  return trim(str).replace(/\s\s+/g, ' ');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.cleanDiacritics"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>cleanDiacritics (str)](#apidoc.element.grunt.util._.cleanDiacritics)
- description and source-code
```javascript
function cleanDiacritics(str) {
    return makeString(str).replace(/.{1}/g, function(c){
      var index = from.indexOf(c);
      return index === -1 ? c : to[index];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.clone"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>clone (value)](#apidoc.element.grunt.util._.clone)
- description and source-code
```javascript
function clone(value) {
  return baseClone(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.cloneDeep"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>cloneDeep (value)](#apidoc.element.grunt.util._.cloneDeep)
- description and source-code
```javascript
function cloneDeep(value) {
  return baseClone(value, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.cloneDeepWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>cloneDeepWith (value, customizer)](#apidoc.element.grunt.util._.cloneDeepWith)
- description and source-code
```javascript
function cloneDeepWith(value, customizer) {
  return baseClone(value, true, customizer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.cloneWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>cloneWith (value, customizer)](#apidoc.element.grunt.util._.cloneWith)
- description and source-code
```javascript
function cloneWith(value, customizer) {
  return baseClone(value, false, customizer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.compact"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>compact (array)](#apidoc.element.grunt.util._.compact)
- description and source-code
```javascript
function compact(array) {
  var index = -1,
      length = array ? array.length : 0,
      resIndex = -1,
      result = [];

  while (++index < length) {
    var value = array[index];
    if (value) {
      result[++resIndex] = value;
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.concat"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>concat ()](#apidoc.element.grunt.util._.concat)
- description and source-code
```javascript
concat = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.cond"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>cond (pairs)](#apidoc.element.grunt.util._.cond)
- description and source-code
```javascript
function cond(pairs) {
  var length = pairs ? pairs.length : 0,
      toIteratee = getIteratee();

  pairs = !length ? [] : arrayMap(pairs, function(pair) {
    if (typeof pair[1] != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    return [toIteratee(pair[0]), pair[1]];
  });

  return rest(function(args) {
    var index = -1;
    while (++index < length) {
      var pair = pairs[index];
      if (apply(pair[0], this, args)) {
        return apply(pair[1], this, args);
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.conforms"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>conforms (source)](#apidoc.element.grunt.util._.conforms)
- description and source-code
```javascript
function conforms(source) {
  return baseConforms(baseClone(source, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.constant"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>constant (value)](#apidoc.element.grunt.util._.constant)
- description and source-code
```javascript
function constant(value) {
  return function() {
    return value;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.count"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>count (str, substr)](#apidoc.element.grunt.util._.count)
- description and source-code
```javascript
count = function (str, substr) {
  str = makeString(str);
  substr = makeString(substr);

  if (str.length === 0 || substr.length === 0) return 0;

  return str.split(substr).length - 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.countBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>countBy (collection, iteratee)](#apidoc.element.grunt.util._.countBy)
- description and source-code
```javascript
countBy = function (collection, iteratee) {
  var func = isArray(collection) ? arrayAggregator : baseAggregator,
      accumulator = initializer ? initializer() : {};

  return func(collection, setter, getIteratee(iteratee), accumulator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.create"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>create (prototype, properties)](#apidoc.element.grunt.util._.create)
- description and source-code
```javascript
function create(prototype, properties) {
  var result = baseCreate(prototype);
  return properties ? baseAssign(result, properties) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.curry"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>curry (func, arity, guard)](#apidoc.element.grunt.util._.curry)
- description and source-code
```javascript
function curry(func, arity, guard) {
  arity = guard ? undefined : arity;
  var result = createWrapper(func, CURRY_FLAG, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = lodash.placeholder || curry.placeholder;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.curryRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>curryRight (func, arity, guard)](#apidoc.element.grunt.util._.curryRight)
- description and source-code
```javascript
function curryRight(func, arity, guard) {
  arity = guard ? undefined : arity;
  var result = createWrapper(func, CURRY_RIGHT_FLAG, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = lodash.placeholder || curryRight.placeholder;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.dasherize"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>dasherize (str)](#apidoc.element.grunt.util._.dasherize)
- description and source-code
```javascript
function dasherize(str) {
  return trim(str).replace(/([A-Z])/g, '-$1').replace(/[-_\s]+/g, '-').toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.debounce"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>debounce (func, wait, options)](#apidoc.element.grunt.util._.debounce)
- description and source-code
```javascript
function debounce(func, wait, options) {
  var args,
      maxTimeoutId,
      result,
      stamp,
      thisArg,
      timeoutId,
      trailingCall,
      lastCalled = 0,
      leading = false,
      maxWait = false,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  wait = toNumber(wait) || 0;
  if (isObject(options)) {
    leading = !!options.leading;
    maxWait = 'maxWait' in options && nativeMax(toNumber(options.maxWait) || 0, wait);
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }

  function cancel() {
    if (timeoutId) {
      clearTimeout(timeoutId);
    }
    if (maxTimeoutId) {
      clearTimeout(maxTimeoutId);
    }
    lastCalled = 0;
    args = maxTimeoutId = thisArg = timeoutId = trailingCall = undefined;
  }

  function complete(isCalled, id) {
    if (id) {
      clearTimeout(id);
    }
    maxTimeoutId = timeoutId = trailingCall = undefined;
    if (isCalled) {
      lastCalled = now();
      result = func.apply(thisArg, args);
      if (!timeoutId && !maxTimeoutId) {
        args = thisArg = undefined;
      }
    }
  }

  function delayed() {
    var remaining = wait - (now() - stamp);
    if (remaining <= 0 || remaining > wait) {
      complete(trailingCall, maxTimeoutId);
    } else {
      timeoutId = setTimeout(delayed, remaining);
    }
  }

  function flush() {
    if ((timeoutId && trailingCall) || (maxTimeoutId && trailing)) {
      result = func.apply(thisArg, args);
    }
    cancel();
    return result;
  }

  function maxDelayed() {
    complete(trailing, timeoutId);
  }

  function debounced() {
    args = arguments;
    stamp = now();
    thisArg = this;
    trailingCall = trailing && (timeoutId || !leading);

    if (maxWait === false) {
      var leadingCall = leading && !timeoutId;
    } else {
      if (!lastCalled && !maxTimeoutId && !leading) {
        lastCalled = stamp;
      }
      var remaining = maxWait - (stamp - lastCalled),
          isCalled = remaining <= 0 || remaining > maxWait;

      if (isCalled) {
        if (maxTimeoutId) {
          maxTimeoutId = clearTimeout(maxTimeoutId);
        }
        lastCalled = stamp;
        result = func.apply(thisArg, args);
      }
      else if (!maxTimeoutId) {
        maxTimeoutId = setTimeout(maxDelayed, remaining);
      }
    }
    if (isCalled && timeoutId) {
      timeoutId = clearTimeout(timeoutId);
    }
    else if (!timeoutId && wait !== maxWait) {
      timeoutId = setTimeout(delayed, wait);
    }
    if (leadingCall) {
      isCalled = true;
      result = func.apply(thisArg, args);
    }
    if (isCalled && !timeoutId && !maxTimeoutId) {
      args = thisArg = undefined;
    }
    return result;
  }
  debounced.cancel = cancel;
  debounced.flush = flush;
  return debounced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.deburr"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>deburr (string)](#apidoc.element.grunt.util._.deburr)
- description and source-code
```javascript
function deburr(string) {
  string = toString(string);
  return string && string.replace(reLatin1, deburrLetter).replace(reComboMark, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.decapitalize"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>decapitalize (str)](#apidoc.element.grunt.util._.decapitalize)
- description and source-code
```javascript
function decapitalize(str) {
  str = makeString(str);
  return str.charAt(0).toLowerCase() + str.slice(1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.dedent"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>dedent (str, pattern)](#apidoc.element.grunt.util._.dedent)
- description and source-code
```javascript
function dedent(str, pattern) {
  str = makeString(str);
  var indent = getIndent(str);
  var reg;

  if (indent === 0) return str;

  if (typeof pattern === 'string') {
    reg = new RegExp('^' + pattern, 'gm');
  } else {
    reg = new RegExp('^[ \\t]{' + indent + '}', 'gm');
  }

  return str.replace(reg, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.defaults"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>defaults ()](#apidoc.element.grunt.util._.defaults)
- description and source-code
```javascript
defaults = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.defaultsDeep"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>defaultsDeep ()](#apidoc.element.grunt.util._.defaultsDeep)
- description and source-code
```javascript
defaultsDeep = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.defer"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>defer ()](#apidoc.element.grunt.util._.defer)
- description and source-code
```javascript
defer = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.delay"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>delay ()](#apidoc.element.grunt.util._.delay)
- description and source-code
```javascript
delay = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.difference"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>difference ()](#apidoc.element.grunt.util._.difference)
- description and source-code
```javascript
difference = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.differenceBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>differenceBy ()](#apidoc.element.grunt.util._.differenceBy)
- description and source-code
```javascript
differenceBy = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.differenceWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>differenceWith ()](#apidoc.element.grunt.util._.differenceWith)
- description and source-code
```javascript
differenceWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.drop"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>drop (array, n, guard)](#apidoc.element.grunt.util._.drop)
- description and source-code
```javascript
function drop(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  n = (guard || n === undefined) ? 1 : toInteger(n);
  return baseSlice(array, n < 0 ? 0 : n, length);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.dropRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>dropRight (array, n, guard)](#apidoc.element.grunt.util._.dropRight)
- description and source-code
```javascript
function dropRight(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  n = (guard || n === undefined) ? 1 : toInteger(n);
  n = length - n;
  return baseSlice(array, 0, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.dropRightWhile"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>dropRightWhile (array, predicate)](#apidoc.element.grunt.util._.dropRightWhile)
- description and source-code
```javascript
function dropRightWhile(array, predicate) {
  return (array && array.length)
    ? baseWhile(array, getIteratee(predicate, 3), true, true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.dropWhile"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>dropWhile (array, predicate)](#apidoc.element.grunt.util._.dropWhile)
- description and source-code
```javascript
function dropWhile(array, predicate) {
  return (array && array.length)
    ? baseWhile(array, getIteratee(predicate, 3), true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.each"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>each (collection, iteratee)](#apidoc.element.grunt.util._.each)
- description and source-code
```javascript
function forEach(collection, iteratee) {
  return (typeof iteratee == 'function' && isArray(collection))
    ? arrayEach(collection, iteratee)
    : baseEach(collection, toFunction(iteratee));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.eachRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>eachRight (collection, iteratee)](#apidoc.element.grunt.util._.eachRight)
- description and source-code
```javascript
function forEachRight(collection, iteratee) {
  return (typeof iteratee == 'function' && isArray(collection))
    ? arrayEachRight(collection, iteratee)
    : baseEachRight(collection, toFunction(iteratee));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.endsWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>endsWith (str, ends, position)](#apidoc.element.grunt.util._.endsWith)
- description and source-code
```javascript
function endsWith(str, ends, position) {
  str = makeString(str);
  ends = '' + ends;
  if (typeof position == 'undefined') {
    position = str.length - ends.length;
  } else {
    position = Math.min(toPositive(position), str.length) - ends.length;
  }
  return position >= 0 && str.indexOf(ends, position) === position;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.eq"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>eq (value, other)](#apidoc.element.grunt.util._.eq)
- description and source-code
```javascript
function eq(value, other) {
  return value === other || (value !== value && other !== other);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.escape"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>escape (string)](#apidoc.element.grunt.util._.escape)
- description and source-code
```javascript
function escape(string) {
  string = toString(string);
  return (string && reHasUnescapedHtml.test(string))
    ? string.replace(reUnescapedHtml, escapeHtmlChar)
    : string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.escapeHTML"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>escapeHTML (str)](#apidoc.element.grunt.util._.escapeHTML)
- description and source-code
```javascript
function escapeHTML(str) {

  return makeString(str).replace(regex, function(m) {
    return '&' + escapeChars[m] + ';';
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.escapeRegExp"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>escapeRegExp (str)](#apidoc.element.grunt.util._.escapeRegExp)
- description and source-code
```javascript
function escapeRegExp(str) {
  return makeString(str).replace(/([.*+?^=!:${}()|[\]\/\\])/g, '\\$1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.every"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>every (collection, predicate, guard)](#apidoc.element.grunt.util._.every)
- description and source-code
```javascript
function every(collection, predicate, guard) {
  var func = isArray(collection) ? arrayEvery : baseEvery;
  if (guard && isIterateeCall(collection, predicate, guard)) {
    predicate = undefined;
  }
  return func(collection, getIteratee(predicate, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.exports"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>exports ()](#apidoc.element.grunt.util._.exports)
- description and source-code
```javascript
exports = function () {
  var result = {};

  for (var prop in this) {
    if (!this.hasOwnProperty(prop) || prop.match(/^(?:include|contains|reverse|join|map)$/)) continue;
    result[prop] = this[prop];
  }

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.extend"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>extend ()](#apidoc.element.grunt.util._.extend)
- description and source-code
```javascript
extend = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.extendWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>extendWith ()](#apidoc.element.grunt.util._.extendWith)
- description and source-code
```javascript
extendWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.fill"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>fill (array, value, start, end)](#apidoc.element.grunt.util._.fill)
- description and source-code
```javascript
function fill(array, value, start, end) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (start && typeof start != 'number' && isIterateeCall(array, value, start)) {
    start = 0;
    end = length;
  }
  return baseFill(array, value, start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.filter"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>filter (collection, predicate)](#apidoc.element.grunt.util._.filter)
- description and source-code
```javascript
function filter(collection, predicate) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  return func(collection, getIteratee(predicate, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.find"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>find (collection, predicate)](#apidoc.element.grunt.util._.find)
- description and source-code
```javascript
function find(collection, predicate) {
  predicate = getIteratee(predicate, 3);
  if (isArray(collection)) {
    var index = baseFindIndex(collection, predicate);
    return index > -1 ? collection[index] : undefined;
  }
  return baseFind(collection, predicate, baseEach);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.findIndex"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>findIndex (array, predicate)](#apidoc.element.grunt.util._.findIndex)
- description and source-code
```javascript
function findIndex(array, predicate) {
  return (array && array.length)
    ? baseFindIndex(array, getIteratee(predicate, 3))
    : -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.findKey"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>findKey (object, predicate)](#apidoc.element.grunt.util._.findKey)
- description and source-code
```javascript
function findKey(object, predicate) {
  return baseFind(object, getIteratee(predicate, 3), baseForOwn, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.findLast"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>findLast (collection, predicate)](#apidoc.element.grunt.util._.findLast)
- description and source-code
```javascript
function findLast(collection, predicate) {
  predicate = getIteratee(predicate, 3);
  if (isArray(collection)) {
    var index = baseFindIndex(collection, predicate, true);
    return index > -1 ? collection[index] : undefined;
  }
  return baseFind(collection, predicate, baseEachRight);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.findLastIndex"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>findLastIndex (array, predicate)](#apidoc.element.grunt.util._.findLastIndex)
- description and source-code
```javascript
function findLastIndex(array, predicate) {
  return (array && array.length)
    ? baseFindIndex(array, getIteratee(predicate, 3), true)
    : -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.findLastKey"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>findLastKey (object, predicate)](#apidoc.element.grunt.util._.findLastKey)
- description and source-code
```javascript
function findLastKey(object, predicate) {
  return baseFind(object, getIteratee(predicate, 3), baseForOwnRight, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.first"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>first (array)](#apidoc.element.grunt.util._.first)
- description and source-code
```javascript
function head(array) {
  return array ? array[0] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.flatMap"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>flatMap (collection, iteratee)](#apidoc.element.grunt.util._.flatMap)
- description and source-code
```javascript
function flatMap(collection, iteratee) {
  return baseFlatten(map(collection, iteratee));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.flatten"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>flatten (array)](#apidoc.element.grunt.util._.flatten)
- description and source-code
```javascript
function flatten(array) {
  var length = array ? array.length : 0;
  return length ? baseFlatten(array) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.flattenDeep"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>flattenDeep (array)](#apidoc.element.grunt.util._.flattenDeep)
- description and source-code
```javascript
function flattenDeep(array) {
  var length = array ? array.length : 0;
  return length ? baseFlatten(array, true) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.flip"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>flip (func)](#apidoc.element.grunt.util._.flip)
- description and source-code
```javascript
function flip(func) {
  return createWrapper(func, FLIP_FLAG);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.floor"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>floor (number, precision)](#apidoc.element.grunt.util._.floor)
- description and source-code
```javascript
floor = function (number, precision) {
  number = toNumber(number);
  precision = toInteger(precision);
  if (precision) {
    // Shift with exponential notation to avoid floating-point issues.
    // See [MDN](https://mdn.io/round#Examples) for more details.
    var pair = (toString(number) + 'e').split('e'),
        value = func(pair[0] + 'e' + (+pair[1] + precision));

    pair = (toString(value) + 'e').split('e');
    return +(pair[0] + 'e' + (+pair[1] - precision));
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.flow"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>flow ()](#apidoc.element.grunt.util._.flow)
- description and source-code
```javascript
flow = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.flowRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>flowRight ()](#apidoc.element.grunt.util._.flowRight)
- description and source-code
```javascript
flowRight = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.forEach"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>forEach (collection, iteratee)](#apidoc.element.grunt.util._.forEach)
- description and source-code
```javascript
function forEach(collection, iteratee) {
  return (typeof iteratee == 'function' && isArray(collection))
    ? arrayEach(collection, iteratee)
    : baseEach(collection, toFunction(iteratee));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.forEachRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>forEachRight (collection, iteratee)](#apidoc.element.grunt.util._.forEachRight)
- description and source-code
```javascript
function forEachRight(collection, iteratee) {
  return (typeof iteratee == 'function' && isArray(collection))
    ? arrayEachRight(collection, iteratee)
    : baseEachRight(collection, toFunction(iteratee));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.forIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>forIn (object, iteratee)](#apidoc.element.grunt.util._.forIn)
- description and source-code
```javascript
function forIn(object, iteratee) {
  return object == null ? object : baseFor(object, toFunction(iteratee), keysIn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.forInRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>forInRight (object, iteratee)](#apidoc.element.grunt.util._.forInRight)
- description and source-code
```javascript
function forInRight(object, iteratee) {
  return object == null ? object : baseForRight(object, toFunction(iteratee), keysIn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.forOwn"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>forOwn (object, iteratee)](#apidoc.element.grunt.util._.forOwn)
- description and source-code
```javascript
function forOwn(object, iteratee) {
  return object && baseForOwn(object, toFunction(iteratee));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.forOwnRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>forOwnRight (object, iteratee)](#apidoc.element.grunt.util._.forOwnRight)
- description and source-code
```javascript
function forOwnRight(object, iteratee) {
  return object && baseForOwnRight(object, toFunction(iteratee));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.fromPairs"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>fromPairs (pairs)](#apidoc.element.grunt.util._.fromPairs)
- description and source-code
```javascript
function fromPairs(pairs) {
  var index = -1,
      length = pairs ? pairs.length : 0,
      result = {};

  while (++index < length) {
    var pair = pairs[index];
    result[pair[0]] = pair[1];
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.functions"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>functions (object)](#apidoc.element.grunt.util._.functions)
- description and source-code
```javascript
function functions(object) {
  return object == null ? [] : baseFunctions(object, keys(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.functionsIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>functionsIn (object)](#apidoc.element.grunt.util._.functionsIn)
- description and source-code
```javascript
function functionsIn(object) {
  return object == null ? [] : baseFunctions(object, keysIn(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.get"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>get (object, path, defaultValue)](#apidoc.element.grunt.util._.get)
- description and source-code
```javascript
function get(object, path, defaultValue) {
  var result = object == null ? undefined : baseGet(object, path);
  return result === undefined ? defaultValue : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.groupBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>groupBy (collection, iteratee)](#apidoc.element.grunt.util._.groupBy)
- description and source-code
```javascript
groupBy = function (collection, iteratee) {
  var func = isArray(collection) ? arrayAggregator : baseAggregator,
      accumulator = initializer ? initializer() : {};

  return func(collection, setter, getIteratee(iteratee), accumulator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.gt"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>gt (value, other)](#apidoc.element.grunt.util._.gt)
- description and source-code
```javascript
function gt(value, other) {
  return value > other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.gte"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>gte (value, other)](#apidoc.element.grunt.util._.gte)
- description and source-code
```javascript
function gte(value, other) {
  return value >= other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.has"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>has (object, path)](#apidoc.element.grunt.util._.has)
- description and source-code
```javascript
function has(object, path) {
  return hasPath(object, path, baseHas);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.hasIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>hasIn (object, path)](#apidoc.element.grunt.util._.hasIn)
- description and source-code
```javascript
function hasIn(object, path) {
  return hasPath(object, path, baseHasIn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.head"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>head (array)](#apidoc.element.grunt.util._.head)
- description and source-code
```javascript
function head(array) {
  return array ? array[0] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.humanize"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>humanize (str)](#apidoc.element.grunt.util._.humanize)
- description and source-code
```javascript
function humanize(str) {
  return capitalize(trim(underscored(str).replace(/_id$/, '').replace(/_/g, ' ')));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.identity"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>identity (value)](#apidoc.element.grunt.util._.identity)
- description and source-code
```javascript
function identity(value) {
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.inRange"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>inRange (number, start, end)](#apidoc.element.grunt.util._.inRange)
- description and source-code
```javascript
function inRange(number, start, end) {
  start = toNumber(start) || 0;
  if (end === undefined) {
    end = start;
    start = 0;
  } else {
    end = toNumber(end) || 0;
  }
  number = toNumber(number);
  return baseInRange(number, start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.includes"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>includes (collection, value, fromIndex, guard)](#apidoc.element.grunt.util._.includes)
- description and source-code
```javascript
function includes(collection, value, fromIndex, guard) {
  collection = isArrayLike(collection) ? collection : values(collection);
  fromIndex = (fromIndex && !guard) ? toInteger(fromIndex) : 0;

  var length = collection.length;
  if (fromIndex < 0) {
    fromIndex = nativeMax(length + fromIndex, 0);
  }
  return isString(collection)
    ? (fromIndex <= length && collection.indexOf(value, fromIndex) > -1)
    : (!!length && baseIndexOf(collection, value, fromIndex) > -1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.indexOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>indexOf (array, value, fromIndex)](#apidoc.element.grunt.util._.indexOf)
- description and source-code
```javascript
function indexOf(array, value, fromIndex) {
  var length = array ? array.length : 0;
  if (!length) {
    return -1;
  }
  fromIndex = toInteger(fromIndex);
  if (fromIndex < 0) {
    fromIndex = nativeMax(length + fromIndex, 0);
  }
  return baseIndexOf(array, value, fromIndex);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.initial"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>initial (array)](#apidoc.element.grunt.util._.initial)
- description and source-code
```javascript
function initial(array) {
  return dropRight(array, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.insert"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>insert (str, i, substr)](#apidoc.element.grunt.util._.insert)
- description and source-code
```javascript
function insert(str, i, substr) {
  return splice(str, i, 0, substr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.intersection"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>intersection ()](#apidoc.element.grunt.util._.intersection)
- description and source-code
```javascript
intersection = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.intersectionBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>intersectionBy ()](#apidoc.element.grunt.util._.intersectionBy)
- description and source-code
```javascript
intersectionBy = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.intersectionWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>intersectionWith ()](#apidoc.element.grunt.util._.intersectionWith)
- description and source-code
```javascript
intersectionWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.invert"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>invert (object, iteratee)](#apidoc.element.grunt.util._.invert)
- description and source-code
```javascript
invert = function (object, iteratee) {
  return baseInverter(object, setter, toIteratee(iteratee), {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.invertBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>invertBy (object, iteratee)](#apidoc.element.grunt.util._.invertBy)
- description and source-code
```javascript
invertBy = function (object, iteratee) {
  return baseInverter(object, setter, toIteratee(iteratee), {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.invoke"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>invoke ()](#apidoc.element.grunt.util._.invoke)
- description and source-code
```javascript
invoke = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.invokeMap"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>invokeMap ()](#apidoc.element.grunt.util._.invokeMap)
- description and source-code
```javascript
invokeMap = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isArguments"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isArguments (value)](#apidoc.element.grunt.util._.isArguments)
- description and source-code
```javascript
function isArguments(value) {
  // Safari 8.1 incorrectly makes 'arguments.callee' enumerable in strict mode.
  return isArrayLikeObject(value) && hasOwnProperty.call(value, 'callee') &&
    (!propertyIsEnumerable.call(value, 'callee') || objectToString.call(value) == argsTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isArray"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isArray ()](#apidoc.element.grunt.util._.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isArrayBuffer"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isArrayBuffer (value)](#apidoc.element.grunt.util._.isArrayBuffer)
- description and source-code
```javascript
function isArrayBuffer(value) {
  return isObjectLike(value) && objectToString.call(value) == arrayBufferTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isArrayLike"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isArrayLike (value)](#apidoc.element.grunt.util._.isArrayLike)
- description and source-code
```javascript
function isArrayLike(value) {
  return value != null &&
    !(typeof value == 'function' && isFunction(value)) && isLength(getLength(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isArrayLikeObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isArrayLikeObject (value)](#apidoc.element.grunt.util._.isArrayLikeObject)
- description and source-code
```javascript
function isArrayLikeObject(value) {
  return isObjectLike(value) && isArrayLike(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isBlank"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isBlank (str)](#apidoc.element.grunt.util._.isBlank)
- description and source-code
```javascript
function isBlank(str) {
  return (/^\s*$/).test(makeString(str));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isBoolean"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isBoolean (value)](#apidoc.element.grunt.util._.isBoolean)
- description and source-code
```javascript
function isBoolean(value) {
  return value === true || value === false ||
    (isObjectLike(value) && objectToString.call(value) == boolTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isBuffer"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isBuffer (value)](#apidoc.element.grunt.util._.isBuffer)
- description and source-code
```javascript
isBuffer = function (value) {
  return value instanceof Buffer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isDate"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isDate (value)](#apidoc.element.grunt.util._.isDate)
- description and source-code
```javascript
function isDate(value) {
  return isObjectLike(value) && objectToString.call(value) == dateTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isElement"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isElement (value)](#apidoc.element.grunt.util._.isElement)
- description and source-code
```javascript
function isElement(value) {
  return !!value && value.nodeType === 1 && isObjectLike(value) && !isPlainObject(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isEmpty"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isEmpty (value)](#apidoc.element.grunt.util._.isEmpty)
- description and source-code
```javascript
function isEmpty(value) {
  if (isArrayLike(value) &&
      (isArray(value) || isString(value) || isFunction(value.splice) || isArguments(value))) {
    return !value.length;
  }
  for (var key in value) {
    if (hasOwnProperty.call(value, key)) {
      return false;
    }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isEqual"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isEqual (value, other)](#apidoc.element.grunt.util._.isEqual)
- description and source-code
```javascript
function isEqual(value, other) {
  return baseIsEqual(value, other);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isEqualWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isEqualWith (value, other, customizer)](#apidoc.element.grunt.util._.isEqualWith)
- description and source-code
```javascript
function isEqualWith(value, other, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  var result = customizer ? customizer(value, other) : undefined;
  return result === undefined ? baseIsEqual(value, other, customizer) : !!result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isError"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isError (value)](#apidoc.element.grunt.util._.isError)
- description and source-code
```javascript
function isError(value) {
  return isObjectLike(value) &&
    typeof value.message == 'string' && objectToString.call(value) == errorTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isFinite"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isFinite (value)](#apidoc.element.grunt.util._.isFinite)
- description and source-code
```javascript
function isFinite(value) {
  return typeof value == 'number' && nativeIsFinite(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isFunction"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isFunction (value)](#apidoc.element.grunt.util._.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  // The use of 'Object#toString' avoids issues with the 'typeof' operator
  // in Safari 8 which returns 'object' for typed array constructors, and
  // PhantomJS 1.9 which returns 'function' for 'NodeList' instances.
  var tag = isObject(value) ? objectToString.call(value) : '';
  return tag == funcTag || tag == genTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isInteger"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isInteger (value)](#apidoc.element.grunt.util._.isInteger)
- description and source-code
```javascript
function isInteger(value) {
  return typeof value == 'number' && value == toInteger(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isLength"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isLength (value)](#apidoc.element.grunt.util._.isLength)
- description and source-code
```javascript
function isLength(value) {
  return typeof value == 'number' && value > -1 && value % 1 == 0 && value <= MAX_SAFE_INTEGER;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isMap"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isMap (value)](#apidoc.element.grunt.util._.isMap)
- description and source-code
```javascript
function isMap(value) {
  return isObjectLike(value) && getTag(value) == mapTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isMatch"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isMatch (object, source)](#apidoc.element.grunt.util._.isMatch)
- description and source-code
```javascript
function isMatch(object, source) {
  return object === source || baseIsMatch(object, source, getMatchData(source));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isMatchWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isMatchWith (object, source, customizer)](#apidoc.element.grunt.util._.isMatchWith)
- description and source-code
```javascript
function isMatchWith(object, source, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return baseIsMatch(object, source, getMatchData(source), customizer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isNaN"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isNaN (value)](#apidoc.element.grunt.util._.isNaN)
- description and source-code
```javascript
function isNaN(value) {
  // An 'NaN' primitive is the only value that is not equal to itself.
  // Perform the 'toStringTag' check first to avoid errors with some ActiveX objects in IE.
  return isNumber(value) && value != +value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isNative"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isNative (value)](#apidoc.element.grunt.util._.isNative)
- description and source-code
```javascript
function isNative(value) {
  if (value == null) {
    return false;
  }
  if (isFunction(value)) {
    return reIsNative.test(funcToString.call(value));
  }
  return isObjectLike(value) &&
    (isHostObject(value) ? reIsNative : reIsHostCtor).test(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isNil"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isNil (value)](#apidoc.element.grunt.util._.isNil)
- description and source-code
```javascript
function isNil(value) {
  return value == null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isNull"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isNull (value)](#apidoc.element.grunt.util._.isNull)
- description and source-code
```javascript
function isNull(value) {
  return value === null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isNumber"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isNumber (value)](#apidoc.element.grunt.util._.isNumber)
- description and source-code
```javascript
function isNumber(value) {
  return typeof value == 'number' ||
    (isObjectLike(value) && objectToString.call(value) == numberTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isObject (value)](#apidoc.element.grunt.util._.isObject)
- description and source-code
```javascript
function isObject(value) {
  var type = typeof value;
  return !!value && (type == 'object' || type == 'function');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isObjectLike"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isObjectLike (value)](#apidoc.element.grunt.util._.isObjectLike)
- description and source-code
```javascript
function isObjectLike(value) {
  return !!value && typeof value == 'object';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isPlainObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isPlainObject (value)](#apidoc.element.grunt.util._.isPlainObject)
- description and source-code
```javascript
function isPlainObject(value) {
  if (!isObjectLike(value) || objectToString.call(value) != objectTag || isHostObject(value)) {
    return false;
  }
  var proto = objectProto;
  if (typeof value.constructor == 'function') {
    proto = getPrototypeOf(value);
  }
  if (proto === null) {
    return true;
  }
  var Ctor = proto.constructor;
  return (typeof Ctor == 'function' &&
    Ctor instanceof Ctor && funcToString.call(Ctor) == objectCtorString);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isRegExp"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isRegExp (value)](#apidoc.element.grunt.util._.isRegExp)
- description and source-code
```javascript
function isRegExp(value) {
  return isObject(value) && objectToString.call(value) == regexpTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isSafeInteger"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isSafeInteger (value)](#apidoc.element.grunt.util._.isSafeInteger)
- description and source-code
```javascript
function isSafeInteger(value) {
  return isInteger(value) && value >= -MAX_SAFE_INTEGER && value <= MAX_SAFE_INTEGER;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isSet"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isSet (value)](#apidoc.element.grunt.util._.isSet)
- description and source-code
```javascript
function isSet(value) {
  return isObjectLike(value) && getTag(value) == setTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isString"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isString (value)](#apidoc.element.grunt.util._.isString)
- description and source-code
```javascript
function isString(value) {
  return typeof value == 'string' ||
    (!isArray(value) && isObjectLike(value) && objectToString.call(value) == stringTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isSymbol"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isSymbol (value)](#apidoc.element.grunt.util._.isSymbol)
- description and source-code
```javascript
function isSymbol(value) {
  return typeof value == 'symbol' ||
    (isObjectLike(value) && objectToString.call(value) == symbolTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isTypedArray"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isTypedArray (value)](#apidoc.element.grunt.util._.isTypedArray)
- description and source-code
```javascript
function isTypedArray(value) {
  return isObjectLike(value) && isLength(value.length) && !!typedArrayTags[objectToString.call(value)];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isUndefined"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isUndefined (value)](#apidoc.element.grunt.util._.isUndefined)
- description and source-code
```javascript
function isUndefined(value) {
  return value === undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isWeakMap"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isWeakMap (value)](#apidoc.element.grunt.util._.isWeakMap)
- description and source-code
```javascript
function isWeakMap(value) {
  return isObjectLike(value) && getTag(value) == weakMapTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.isWeakSet"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>isWeakSet (value)](#apidoc.element.grunt.util._.isWeakSet)
- description and source-code
```javascript
function isWeakSet(value) {
  return isObjectLike(value) && objectToString.call(value) == weakSetTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.iteratee"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>iteratee (func)](#apidoc.element.grunt.util._.iteratee)
- description and source-code
```javascript
function iteratee(func) {
  return baseIteratee(typeof func == 'function' ? func : baseClone(func, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.join"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>join (array, separator)](#apidoc.element.grunt.util._.join)
- description and source-code
```javascript
function join(array, separator) {
  return array ? nativeJoin.call(array, separator) : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.kebabCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>kebabCase (string)](#apidoc.element.grunt.util._.kebabCase)
- description and source-code
```javascript
kebabCase = function (string) {
  return arrayReduce(words(deburr(string)), callback, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.keyBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>keyBy (collection, iteratee)](#apidoc.element.grunt.util._.keyBy)
- description and source-code
```javascript
keyBy = function (collection, iteratee) {
  var func = isArray(collection) ? arrayAggregator : baseAggregator,
      accumulator = initializer ? initializer() : {};

  return func(collection, setter, getIteratee(iteratee), accumulator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.keys"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>keys (object)](#apidoc.element.grunt.util._.keys)
- description and source-code
```javascript
function keys(object) {
  var isProto = isPrototype(object);
  if (!(isProto || isArrayLike(object))) {
    return baseKeys(object);
  }
  var indexes = indexKeys(object),
      skipIndexes = !!indexes,
      result = indexes || [],
      length = result.length;

  for (var key in object) {
    if (baseHas(object, key) &&
        !(skipIndexes && (key == 'length' || isIndex(key, length))) &&
        !(isProto && key == 'constructor')) {
      result.push(key);
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.keysIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>keysIn (object)](#apidoc.element.grunt.util._.keysIn)
- description and source-code
```javascript
function keysIn(object) {
  var index = -1,
      isProto = isPrototype(object),
      props = baseKeysIn(object),
      propsLength = props.length,
      indexes = indexKeys(object),
      skipIndexes = !!indexes,
      result = indexes || [],
      length = result.length;

  while (++index < propsLength) {
    var key = props[index];
    if (!(skipIndexes && (key == 'length' || isIndex(key, length))) &&
        !(key == 'constructor' && (isProto || !hasOwnProperty.call(object, key)))) {
      result.push(key);
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.last"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>last (array)](#apidoc.element.grunt.util._.last)
- description and source-code
```javascript
function last(array) {
  var length = array ? array.length : 0;
  return length ? array[length - 1] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lastIndexOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.grunt.util._.lastIndexOf)
- description and source-code
```javascript
function lastIndexOf(array, value, fromIndex) {
  var length = array ? array.length : 0;
  if (!length) {
    return -1;
  }
  var index = length;
  if (fromIndex !== undefined) {
    index = toInteger(fromIndex);
    index = (index < 0 ? nativeMax(length + index, 0) : nativeMin(index, length - 1)) + 1;
  }
  if (value !== value) {
    return indexOfNaN(array, index, true);
  }
  while (index--) {
    if (array[index] === value) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.levenshtein"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>levenshtein (str1, str2)](#apidoc.element.grunt.util._.levenshtein)
- description and source-code
```javascript
function levenshtein(str1, str2) {
  'use strict';
  str1 = makeString(str1);
  str2 = makeString(str2);

  // Short cut cases
  if (str1 === str2) return 0;
  if (!str1 || !str2) return Math.max(str1.length, str2.length);

  // two rows
  var prevRow = new Array(str2.length + 1);

  // initialise previous row
  for (var i = 0; i < prevRow.length; ++i) {
    prevRow[i] = i;
  }

  // calculate current row distance from previous row
  for (i = 0; i < str1.length; ++i) {
    var nextCol = i + 1;

    for (var j = 0; j < str2.length; ++j) {
      var curCol = nextCol;

      // substution
      nextCol = prevRow[j] + ( (str1.charAt(i) === str2.charAt(j)) ? 0 : 1 );
      // insertion
      var tmp = curCol + 1;
      if (nextCol > tmp) {
        nextCol = tmp;
      }
      // deletion
      tmp = prevRow[j + 1] + 1;
      if (nextCol > tmp) {
        nextCol = tmp;
      }

      // copy current col value into previous (in preparation for next iteration)
      prevRow[j] = curCol;
    }

    // copy last col value into previous (in preparation for next iteration)
    prevRow[j] = nextCol;
  }

  return nextCol;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lines"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lines (str)](#apidoc.element.grunt.util._.lines)
- description and source-code
```javascript
function lines(str) {
  if (str == null) return [];
  return String(str).split(/\r\n?|\n/);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.ljust"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>ljust (str, length, padStr)](#apidoc.element.grunt.util._.ljust)
- description and source-code
```javascript
function rpad(str, length, padStr) {
  return pad(str, length, padStr, 'right');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lowerCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lowerCase (string)](#apidoc.element.grunt.util._.lowerCase)
- description and source-code
```javascript
lowerCase = function (string) {
  return arrayReduce(words(deburr(string)), callback, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lowerFirst"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lowerFirst (string)](#apidoc.element.grunt.util._.lowerFirst)
- description and source-code
```javascript
lowerFirst = function (string) {
  string = toString(string);

  var strSymbols = reHasComplexSymbol.test(string) ? stringToArray(string) : undefined,
      chr = strSymbols ? strSymbols[0] : string.charAt(0),
      trailing = strSymbols ? strSymbols.slice(1).join('') : string.slice(1);

  return chr[methodName]() + trailing;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lpad (str, length, padStr)](#apidoc.element.grunt.util._.lpad)
- description and source-code
```javascript
function lpad(str, length, padStr) {
  return pad(str, length, padStr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lrpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lrpad (str, length, padStr)](#apidoc.element.grunt.util._.lrpad)
- description and source-code
```javascript
function lrpad(str, length, padStr) {
  return pad(str, length, padStr, 'both');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lstrip"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lstrip (str, characters)](#apidoc.element.grunt.util._.lstrip)
- description and source-code
```javascript
function ltrim(str, characters) {
  str = makeString(str);
  if (!characters && nativeTrimLeft) return nativeTrimLeft.call(str);
  characters = defaultToWhiteSpace(characters);
  return str.replace(new RegExp('^' + characters + '+'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lt"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lt (value, other)](#apidoc.element.grunt.util._.lt)
- description and source-code
```javascript
function lt(value, other) {
  return value < other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.lte"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>lte (value, other)](#apidoc.element.grunt.util._.lte)
- description and source-code
```javascript
function lte(value, other) {
  return value <= other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.ltrim"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>ltrim (str, characters)](#apidoc.element.grunt.util._.ltrim)
- description and source-code
```javascript
function ltrim(str, characters) {
  str = makeString(str);
  if (!characters && nativeTrimLeft) return nativeTrimLeft.call(str);
  characters = defaultToWhiteSpace(characters);
  return str.replace(new RegExp('^' + characters + '+'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.map"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>map (collection, iteratee)](#apidoc.element.grunt.util._.map)
- description and source-code
```javascript
function map(collection, iteratee) {
  var func = isArray(collection) ? arrayMap : baseMap;
  return func(collection, getIteratee(iteratee, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.mapChars"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>mapChars (str, callback)](#apidoc.element.grunt.util._.mapChars)
- description and source-code
```javascript
mapChars = function (str, callback) {
  str = makeString(str);

  if (str.length === 0 || typeof callback !== 'function') return str;

  return str.replace(/./g, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.mapKeys"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>mapKeys (object, iteratee)](#apidoc.element.grunt.util._.mapKeys)
- description and source-code
```javascript
function mapKeys(object, iteratee) {
  var result = {};
  iteratee = getIteratee(iteratee, 3);

  baseForOwn(object, function(value, key, object) {
    result[iteratee(value, key, object)] = value;
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.mapValues"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>mapValues (object, iteratee)](#apidoc.element.grunt.util._.mapValues)
- description and source-code
```javascript
function mapValues(object, iteratee) {
  var result = {};
  iteratee = getIteratee(iteratee, 3);

  baseForOwn(object, function(value, key, object) {
    result[key] = iteratee(value, key, object);
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.matches"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>matches (source)](#apidoc.element.grunt.util._.matches)
- description and source-code
```javascript
function matches(source) {
  return baseMatches(baseClone(source, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.matchesProperty"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>matchesProperty (path, srcValue)](#apidoc.element.grunt.util._.matchesProperty)
- description and source-code
```javascript
function matchesProperty(path, srcValue) {
  return baseMatchesProperty(path, baseClone(srcValue, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.max"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>max (array)](#apidoc.element.grunt.util._.max)
- description and source-code
```javascript
function max(array) {
  return (array && array.length)
    ? baseExtremum(array, identity, gt)
    : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.maxBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>maxBy (array, iteratee)](#apidoc.element.grunt.util._.maxBy)
- description and source-code
```javascript
function maxBy(array, iteratee) {
  return (array && array.length)
    ? baseExtremum(array, getIteratee(iteratee), gt)
    : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.mean"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>mean (array)](#apidoc.element.grunt.util._.mean)
- description and source-code
```javascript
function mean(array) {
  return sum(array) / (array ? array.length : 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.memoize"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>memoize (func, resolver)](#apidoc.element.grunt.util._.memoize)
- description and source-code
```javascript
function memoize(func, resolver) {
  if (typeof func != 'function' || (resolver && typeof resolver != 'function')) {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  var memoized = function() {
    var args = arguments,
        key = resolver ? resolver.apply(this, args) : args[0],
        cache = memoized.cache;

    if (cache.has(key)) {
      return cache.get(key);
    }
    var result = func.apply(this, args);
    memoized.cache = cache.set(key, result);
    return result;
  };
  memoized.cache = new memoize.Cache;
  return memoized;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.merge"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>merge ()](#apidoc.element.grunt.util._.merge)
- description and source-code
```javascript
merge = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.mergeWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>mergeWith ()](#apidoc.element.grunt.util._.mergeWith)
- description and source-code
```javascript
mergeWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.method"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>method ()](#apidoc.element.grunt.util._.method)
- description and source-code
```javascript
method = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.methodOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>methodOf ()](#apidoc.element.grunt.util._.methodOf)
- description and source-code
```javascript
methodOf = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.min"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>min (array)](#apidoc.element.grunt.util._.min)
- description and source-code
```javascript
function min(array) {
  return (array && array.length)
    ? baseExtremum(array, identity, lt)
    : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.minBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>minBy (array, iteratee)](#apidoc.element.grunt.util._.minBy)
- description and source-code
```javascript
function minBy(array, iteratee) {
  return (array && array.length)
    ? baseExtremum(array, getIteratee(iteratee), lt)
    : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.mixin"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>mixin (object, source, options)](#apidoc.element.grunt.util._.mixin)
- description and source-code
```javascript
function mixin(object, source, options) {
  var props = keys(source),
      methodNames = baseFunctions(source, props);

  if (options == null &&
      !(isObject(source) && (methodNames.length || !props.length))) {
    options = source;
    source = object;
    object = this;
    methodNames = baseFunctions(source, keys(source));
  }
  var chain = (isObject(options) && 'chain' in options) ? options.chain : true,
      isFunc = isFunction(object);

  arrayEach(methodNames, function(methodName) {
    var func = source[methodName];
    object[methodName] = func;
    if (isFunc) {
      object.prototype[methodName] = function() {
        var chainAll = this.__chain__;
        if (chain || chainAll) {
          var result = object(this.__wrapped__),
              actions = result.__actions__ = copyArray(this.__actions__);

          actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
          result.__chain__ = chainAll;
          return result;
        }
        return func.apply(object, arrayPush([this.value()], arguments));
      };
    }
  });

  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.naturalCmp"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>naturalCmp (str1, str2)](#apidoc.element.grunt.util._.naturalCmp)
- description and source-code
```javascript
function naturalCmp(str1, str2) {
  if (str1 == str2) return 0;
  if (!str1) return -1;
  if (!str2) return 1;

  var cmpRegex = /(\.\d+|\d+|\D+)/g,
    tokens1 = String(str1).match(cmpRegex),
    tokens2 = String(str2).match(cmpRegex),
    count = Math.min(tokens1.length, tokens2.length);

  for (var i = 0; i < count; i++) {
    var a = tokens1[i],
      b = tokens2[i];

    if (a !== b) {
      var num1 = +a;
      var num2 = +b;
      if (num1 === num1 && num2 === num2) {
        return num1 > num2 ? 1 : -1;
      }
      return a < b ? -1 : 1;
    }
  }

  if (tokens1.length != tokens2.length)
    return tokens1.length - tokens2.length;

  return str1 < str2 ? -1 : 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.negate"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>negate (predicate)](#apidoc.element.grunt.util._.negate)
- description and source-code
```javascript
function negate(predicate) {
  if (typeof predicate != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  return function() {
    return !predicate.apply(this, arguments);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.noConflict"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>noConflict ()](#apidoc.element.grunt.util._.noConflict)
- description and source-code
```javascript
function noConflict() {
  if (root._ === this) {
    root._ = oldDash;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.noop"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>noop ()](#apidoc.element.grunt.util._.noop)
- description and source-code
```javascript
function noop() {
  // No operation performed.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.now"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>now ()](#apidoc.element.grunt.util._.now)
- description and source-code
```javascript
function now() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.nthArg"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>nthArg (n)](#apidoc.element.grunt.util._.nthArg)
- description and source-code
```javascript
function nthArg(n) {
  n = toInteger(n);
  return function() {
    return arguments[n];
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.numberFormat"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>numberFormat (number, dec, dsep, tsep)](#apidoc.element.grunt.util._.numberFormat)
- description and source-code
```javascript
function numberFormat(number, dec, dsep, tsep) {
  if (isNaN(number) || number == null) return '';

  number = number.toFixed(~~dec);
  tsep = typeof tsep == 'string' ? tsep : ',';

  var parts = number.split('.'),
    fnums = parts[0],
    decimals = parts[1] ? (dsep || '.') + parts[1] : '';

  return fnums.replace(/(\d)(?=(?:\d{3})+$)/g, '$1' + tsep) + decimals;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.omit"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>omit ()](#apidoc.element.grunt.util._.omit)
- description and source-code
```javascript
omit = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.omitBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>omitBy (object, predicate)](#apidoc.element.grunt.util._.omitBy)
- description and source-code
```javascript
function omitBy(object, predicate) {
  predicate = getIteratee(predicate, 2);
  return basePickBy(object, function(value, key) {
    return !predicate(value, key);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.once"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>once (func)](#apidoc.element.grunt.util._.once)
- description and source-code
```javascript
function once(func) {
  return before(2, func);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.orderBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>orderBy (collection, iteratees, orders, guard)](#apidoc.element.grunt.util._.orderBy)
- description and source-code
```javascript
function orderBy(collection, iteratees, orders, guard) {
  if (collection == null) {
    return [];
  }
  if (!isArray(iteratees)) {
    iteratees = iteratees == null ? [] : [iteratees];
  }
  orders = guard ? undefined : orders;
  if (!isArray(orders)) {
    orders = orders == null ? [] : [orders];
  }
  return baseOrderBy(collection, iteratees, orders);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.over"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>over ()](#apidoc.element.grunt.util._.over)
- description and source-code
```javascript
over = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.overArgs"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>overArgs ()](#apidoc.element.grunt.util._.overArgs)
- description and source-code
```javascript
overArgs = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.overEvery"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>overEvery ()](#apidoc.element.grunt.util._.overEvery)
- description and source-code
```javascript
overEvery = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.overSome"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>overSome ()](#apidoc.element.grunt.util._.overSome)
- description and source-code
```javascript
overSome = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.pad"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>pad (str, length, padStr, type)](#apidoc.element.grunt.util._.pad)
- description and source-code
```javascript
function pad(str, length, padStr, type) {
  str = makeString(str);
  length = ~~length;

  var padlen = 0;

  if (!padStr)
    padStr = ' ';
  else if (padStr.length > 1)
    padStr = padStr.charAt(0);

  switch (type) {
    case 'right':
      padlen = length - str.length;
      return str + strRepeat(padStr, padlen);
    case 'both':
      padlen = length - str.length;
      return strRepeat(padStr, Math.ceil(padlen / 2)) + str + strRepeat(padStr, Math.floor(padlen / 2));
    default: // 'left'
      padlen = length - str.length;
      return strRepeat(padStr, padlen) + str;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.padEnd"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>padEnd (string, length, chars)](#apidoc.element.grunt.util._.padEnd)
- description and source-code
```javascript
function padEnd(string, length, chars) {
  string = toString(string);
  return string + createPadding(string, length, chars);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.padStart"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>padStart (string, length, chars)](#apidoc.element.grunt.util._.padStart)
- description and source-code
```javascript
function padStart(string, length, chars) {
  string = toString(string);
  return createPadding(string, length, chars) + string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.parseInt"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>parseInt (string, radix, guard)](#apidoc.element.grunt.util._.parseInt)
- description and source-code
```javascript
function parseInt(string, radix, guard) {
  // Chrome fails to trim leading <BOM> whitespace characters.
  // See https://code.google.com/p/v8/issues/detail?id=3109 for more details.
  if (guard || radix == null) {
    radix = 0;
  } else if (radix) {
    radix = +radix;
  }
  string = toString(string).replace(reTrim, '');
  return nativeParseInt(string, radix || (reHasHexPrefix.test(string) ? 16 : 10));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.partial"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>partial ()](#apidoc.element.grunt.util._.partial)
- description and source-code
```javascript
partial = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.partialRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>partialRight ()](#apidoc.element.grunt.util._.partialRight)
- description and source-code
```javascript
partialRight = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.partition"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>partition (collection, iteratee)](#apidoc.element.grunt.util._.partition)
- description and source-code
```javascript
partition = function (collection, iteratee) {
  var func = isArray(collection) ? arrayAggregator : baseAggregator,
      accumulator = initializer ? initializer() : {};

  return func(collection, setter, getIteratee(iteratee), accumulator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.pick"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>pick ()](#apidoc.element.grunt.util._.pick)
- description and source-code
```javascript
pick = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.pickBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>pickBy (object, predicate)](#apidoc.element.grunt.util._.pickBy)
- description and source-code
```javascript
function pickBy(object, predicate) {
  return object == null ? {} : basePickBy(object, getIteratee(predicate, 2));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.pred"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>pred (str)](#apidoc.element.grunt.util._.pred)
- description and source-code
```javascript
function succ(str) {
  return adjacent(str, -1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.property"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>property (path)](#apidoc.element.grunt.util._.property)
- description and source-code
```javascript
function property(path) {
  return isKey(path) ? baseProperty(path) : basePropertyDeep(path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.propertyOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>propertyOf (object)](#apidoc.element.grunt.util._.propertyOf)
- description and source-code
```javascript
function propertyOf(object) {
  return function(path) {
    return object == null ? undefined : baseGet(object, path);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prune"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>prune (str, length, pruneStr)](#apidoc.element.grunt.util._.prune)
- description and source-code
```javascript
function prune(str, length, pruneStr) {
  str = makeString(str);
  length = ~~length;
  pruneStr = pruneStr != null ? String(pruneStr) : '...';

  if (str.length <= length) return str;

  var tmpl = function(c) {
    return c.toUpperCase() !== c.toLowerCase() ? 'A' : ' ';
  },
    template = str.slice(0, length + 1).replace(/.(?=\W*\w*$)/g, tmpl); // 'Hello, world' -> 'HellAA AAAAA'

  if (template.slice(template.length - 2).match(/\w\w/))
    template = template.replace(/\s*\S+$/, '');
  else
    template = rtrim(template.slice(0, template.length - 1));

  return (template + pruneStr).length > str.length ? str : str.slice(0, template.length) + pruneStr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.pull"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>pull ()](#apidoc.element.grunt.util._.pull)
- description and source-code
```javascript
pull = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.pullAll"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>pullAll (array, values)](#apidoc.element.grunt.util._.pullAll)
- description and source-code
```javascript
function pullAll(array, values) {
  return (array && array.length && values && values.length)
    ? basePullAll(array, values)
    : array;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.pullAllBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>pullAllBy (array, values, iteratee)](#apidoc.element.grunt.util._.pullAllBy)
- description and source-code
```javascript
function pullAllBy(array, values, iteratee) {
  return (array && array.length && values && values.length)
    ? basePullAllBy(array, values, getIteratee(iteratee))
    : array;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.pullAt"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>pullAt ()](#apidoc.element.grunt.util._.pullAt)
- description and source-code
```javascript
pullAt = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.q"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>q (str, quoteChar)](#apidoc.element.grunt.util._.q)
- description and source-code
```javascript
function quote(str, quoteChar) {
  return surround(str, quoteChar || '"');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.quote"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>quote (str, quoteChar)](#apidoc.element.grunt.util._.quote)
- description and source-code
```javascript
function quote(str, quoteChar) {
  return surround(str, quoteChar || '"');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.random"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>random (lower, upper, floating)](#apidoc.element.grunt.util._.random)
- description and source-code
```javascript
function random(lower, upper, floating) {
  if (floating && typeof floating != 'boolean' && isIterateeCall(lower, upper, floating)) {
    upper = floating = undefined;
  }
  if (floating === undefined) {
    if (typeof upper == 'boolean') {
      floating = upper;
      upper = undefined;
    }
    else if (typeof lower == 'boolean') {
      floating = lower;
      lower = undefined;
    }
  }
  if (lower === undefined && upper === undefined) {
    lower = 0;
    upper = 1;
  }
  else {
    lower = toNumber(lower) || 0;
    if (upper === undefined) {
      upper = lower;
      lower = 0;
    } else {
      upper = toNumber(upper) || 0;
    }
  }
  if (lower > upper) {
    var temp = lower;
    lower = upper;
    upper = temp;
  }
  if (floating || lower % 1 || upper % 1) {
    var rand = nativeRandom();
    return nativeMin(lower + (rand * (upper - lower + freeParseFloat('1e-' + ((rand + '').length - 1)))), upper);
  }
  return baseRandom(lower, upper);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.range"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>range (start, end, step)](#apidoc.element.grunt.util._.range)
- description and source-code
```javascript
range = function (start, end, step) {
  if (step && typeof step != 'number' && isIterateeCall(start, end, step)) {
    end = step = undefined;
  }
  // Ensure the sign of '-0' is preserved.
  start = toNumber(start);
  start = start === start ? start : 0;
  if (end === undefined) {
    end = start;
    start = 0;
  } else {
    end = toNumber(end) || 0;
  }
  step = step === undefined ? (start < end ? 1 : -1) : (toNumber(step) || 0);
  return baseRange(start, end, step, fromRight);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.rangeRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>rangeRight (start, end, step)](#apidoc.element.grunt.util._.rangeRight)
- description and source-code
```javascript
rangeRight = function (start, end, step) {
  if (step && typeof step != 'number' && isIterateeCall(start, end, step)) {
    end = step = undefined;
  }
  // Ensure the sign of '-0' is preserved.
  start = toNumber(start);
  start = start === start ? start : 0;
  if (end === undefined) {
    end = start;
    start = 0;
  } else {
    end = toNumber(end) || 0;
  }
  step = step === undefined ? (start < end ? 1 : -1) : (toNumber(step) || 0);
  return baseRange(start, end, step, fromRight);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.rearg"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>rearg ()](#apidoc.element.grunt.util._.rearg)
- description and source-code
```javascript
rearg = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.reduce"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>reduce (collection, iteratee, accumulator)](#apidoc.element.grunt.util._.reduce)
- description and source-code
```javascript
function reduce(collection, iteratee, accumulator) {
  var func = isArray(collection) ? arrayReduce : baseReduce,
      initAccum = arguments.length < 3;

  return func(collection, getIteratee(iteratee, 4), accumulator, initAccum, baseEach);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.reduceRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>reduceRight (collection, iteratee, accumulator)](#apidoc.element.grunt.util._.reduceRight)
- description and source-code
```javascript
function reduceRight(collection, iteratee, accumulator) {
  var func = isArray(collection) ? arrayReduceRight : baseReduce,
      initAccum = arguments.length < 3;

  return func(collection, getIteratee(iteratee, 4), accumulator, initAccum, baseEachRight);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.reject"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>reject (collection, predicate)](#apidoc.element.grunt.util._.reject)
- description and source-code
```javascript
function reject(collection, predicate) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  predicate = getIteratee(predicate, 3);
  return func(collection, function(value, index, collection) {
    return !predicate(value, index, collection);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.remove"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>remove (array, predicate)](#apidoc.element.grunt.util._.remove)
- description and source-code
```javascript
function remove(array, predicate) {
  var result = [];
  if (!(array && array.length)) {
    return result;
  }
  var index = -1,
      indexes = [],
      length = array.length;

  predicate = getIteratee(predicate, 3);
  while (++index < length) {
    var value = array[index];
    if (predicate(value, index, array)) {
      result.push(value);
      indexes.push(index);
    }
  }
  basePullAt(array, indexes);
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.repeat"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>repeat (str, qty, separator)](#apidoc.element.grunt.util._.repeat)
- description and source-code
```javascript
function repeat(str, qty, separator) {
  str = makeString(str);

  qty = ~~qty;

  // using faster implementation if separator is not needed;
  if (separator == null) return strRepeat(str, qty);

  // this one is about 300x slower in Google Chrome
<span class="apidocCodeCommentSpan">  /*eslint no-empty: 0*/
</span>  for (var repeat = []; qty > 0; repeat[--qty] = str) {}
  return repeat.join(separator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.replace"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>replace ()](#apidoc.element.grunt.util._.replace)
- description and source-code
```javascript
function replace() {
  var args = arguments,
      string = toString(args[0]);

  return args.length < 3 ? string : string.replace(args[1], args[2]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.replaceAll"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>replaceAll (str, find, replace, ignorecase)](#apidoc.element.grunt.util._.replaceAll)
- description and source-code
```javascript
function replaceAll(str, find, replace, ignorecase) {
  var flags = (ignorecase === true)?'gi':'g';
  var reg = new RegExp(find, flags);

  return makeString(str).replace(reg, replace);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.rest"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>rest (func, start)](#apidoc.element.grunt.util._.rest)
- description and source-code
```javascript
function rest(func, start) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  start = nativeMax(start === undefined ? (func.length - 1) : toInteger(start), 0);
  return function() {
    var args = arguments,
        index = -1,
        length = nativeMax(args.length - start, 0),
        array = Array(length);

    while (++index < length) {
      array[index] = args[start + index];
    }
    switch (start) {
      case 0: return func.call(this, array);
      case 1: return func.call(this, args[0], array);
      case 2: return func.call(this, args[0], args[1], array);
    }
    var otherArgs = Array(start + 1);
    index = -1;
    while (++index < start) {
      otherArgs[index] = args[index];
    }
    otherArgs[start] = array;
    return apply(func, this, otherArgs);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.result"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>result (object, path, defaultValue)](#apidoc.element.grunt.util._.result)
- description and source-code
```javascript
function result(object, path, defaultValue) {
  if (!isKey(path, object)) {
    path = baseToPath(path);
    var result = get(object, path);
    object = parent(object, path);
  } else {
    result = object == null ? undefined : object[path];
  }
  if (result === undefined) {
    result = defaultValue;
  }
  return isFunction(result) ? result.call(object) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.reverse"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>reverse (array)](#apidoc.element.grunt.util._.reverse)
- description and source-code
```javascript
function reverse(array) {
  return array ? nativeReverse.call(array) : array;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.rjust"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>rjust (str, length, padStr)](#apidoc.element.grunt.util._.rjust)
- description and source-code
```javascript
function lpad(str, length, padStr) {
  return pad(str, length, padStr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.round"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>round (number, precision)](#apidoc.element.grunt.util._.round)
- description and source-code
```javascript
round = function (number, precision) {
  number = toNumber(number);
  precision = toInteger(precision);
  if (precision) {
    // Shift with exponential notation to avoid floating-point issues.
    // See [MDN](https://mdn.io/round#Examples) for more details.
    var pair = (toString(number) + 'e').split('e'),
        value = func(pair[0] + 'e' + (+pair[1] + precision));

    pair = (toString(value) + 'e').split('e');
    return +(pair[0] + 'e' + (+pair[1] - precision));
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.rpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>rpad (str, length, padStr)](#apidoc.element.grunt.util._.rpad)
- description and source-code
```javascript
function rpad(str, length, padStr) {
  return pad(str, length, padStr, 'right');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.rstrip"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>rstrip (str, characters)](#apidoc.element.grunt.util._.rstrip)
- description and source-code
```javascript
function rtrim(str, characters) {
  str = makeString(str);
  if (!characters && nativeTrimRight) return nativeTrimRight.call(str);
  characters = defaultToWhiteSpace(characters);
  return str.replace(new RegExp(characters + '+$'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.rtrim"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>rtrim (str, characters)](#apidoc.element.grunt.util._.rtrim)
- description and source-code
```javascript
function rtrim(str, characters) {
  str = makeString(str);
  if (!characters && nativeTrimRight) return nativeTrimRight.call(str);
  characters = defaultToWhiteSpace(characters);
  return str.replace(new RegExp(characters + '+$'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.runInContext"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>runInContext (context)](#apidoc.element.grunt.util._.runInContext)
- description and source-code
```javascript
function runInContext(context) {
  context = context ? _.defaults({}, context, _.pick(root, contextProps)) : root;

<span class="apidocCodeCommentSpan">  /** Built-in constructor references. */
</span>  var Date = context.Date,
      Error = context.Error,
      Math = context.Math,
      RegExp = context.RegExp,
      TypeError = context.TypeError;

  /** Used for built-in method references. */
  var arrayProto = context.Array.prototype,
      objectProto = context.Object.prototype;

  /** Used to resolve the decompiled source of functions. */
  var funcToString = context.Function.prototype.toString;

  /** Used to check objects for own properties. */
  var hasOwnProperty = objectProto.hasOwnProperty;

  /** Used to generate unique IDs. */
  var idCounter = 0;

  /** Used to infer the 'Object' constructor. */
  var objectCtorString = funcToString.call(Object);

  /**
   * Used to resolve the ['toStringTag'](http://ecma-international.org/ecma-262/6.0/#sec-object.prototype.tostring)
   * of values.
   */
  var objectToString = objectProto.toString;

  /** Used to restore the original '_' reference in '_.noConflict'. */
  var oldDash = root._;

  /** Used to detect if a method is native. */
  var reIsNative = RegExp('^' +
    funcToString.call(hasOwnProperty).replace(reRegExpChar, '\\$&')
    .replace(/hasOwnProperty|(function).*?(?=\\\()| for .+?(?=\\\])/g, '$1.*?') + '$'
  );

  /** Built-in value references. */
  var Buffer = moduleExports ? context.Buffer : undefined,
      Reflect = context.Reflect,
      Symbol = context.Symbol,
      Uint8Array = context.Uint8Array,
      clearTimeout = context.clearTimeout,
      enumerate = Reflect ? Reflect.enumerate : undefined,
      getPrototypeOf = Object.getPrototypeOf,
      getOwnPropertySymbols = Object.getOwnPropertySymbols,
      iteratorSymbol = typeof (iteratorSymbol = Symbol && Symbol.iterator) == 'symbol' ? iteratorSymbol : undefined,
      propertyIsEnumerable = objectProto.propertyIsEnumerable,
      setTimeout = context.setTimeout,
      splice = arrayProto.splice;

  /* Built-in method references for those with the same name as other 'lodash' methods. */
  var nativeCeil = Math.ceil,
      nativeFloor = Math.floor,
      nativeIsFinite = context.isFinite,
      nativeJoin = arrayProto.join,
      nativeKeys = Object.keys,
      nativeMax = Math.max,
      nativeMin = Math.min,
      nativeParseInt = context.parseInt,
      nativeRandom = Math.random,
      nativeReverse = arrayProto.reverse;

  /* Built-in method references that are verified to be native. */
  var Map = getNative(context, 'Map'),
      Set = getNative(context, 'Set'),
      WeakMap = getNative(context, 'WeakMap'),
      nativeCreate = getNative(Object, 'create');

  /** Used to store function metadata. */
  var metaMap = WeakMap && new WeakMap;

  /** Used to detect maps, sets, and weakmaps. */
  var mapCtorString = Map ? funcToString.call(Map) : '',
      setCtorString = Set ? funcToString.call(Set) : '',
      weakMapCtorString = WeakMap ? funcToString.call(WeakMap) : '';

  /** Used to convert symbols to primitives and strings. */
  var symbolProto = Symbol ? Symbol.prototype : undefined,
      symbolValueOf = Symbol ? symbolProto.valueOf : undefined,
      symbolToString = Symbol ? symbolProto.toString : undefined;

  /** Used to lookup unminified function names. */
  var realNames = {};

  /*------------------------------------------------------------------------*/

  /**
   * Creates a 'lodash' object which wraps 'value' to enable implicit method
   * chaining. Methods that operate on and return arrays, collections, and
   * functions can be chained together. Methods that retrieve a single value or
   * may return a primitive value will automatically end the chain sequence and
   * return the unwrapped value. Otherwise, the value must be unwrapped with
   * '_#value'.
   *
   * Explicit chaining, which must be unwrapped with '_#value' in all cases,
   * may be enabled using '_.chain'.
   *
   * The execution of chained methods is lazy, that is, it's deferred until
   * '_#value' is implicitly or explicitly called.
   *
   * Lazy ev ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sample"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sample (collection)](#apidoc.element.grunt.util._.sample)
- description and source-code
```javascript
function sample(collection) {
  var array = isArrayLike(collection) ? collection : values(collection),
      length = array.length;

  return length > 0 ? array[baseRandom(0, length - 1)] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sampleSize"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sampleSize (collection, n)](#apidoc.element.grunt.util._.sampleSize)
- description and source-code
```javascript
function sampleSize(collection, n) {
  var index = -1,
      result = toArray(collection),
      length = result.length,
      lastIndex = length - 1;

  n = baseClamp(toInteger(n), 0, length);
  while (++index < n) {
    var rand = baseRandom(index, lastIndex),
        value = result[rand];

    result[rand] = result[index];
    result[index] = value;
  }
  result.length = n;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.set"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>set (object, path, value)](#apidoc.element.grunt.util._.set)
- description and source-code
```javascript
function set(object, path, value) {
  return object == null ? object : baseSet(object, path, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.setWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>setWith (object, path, value, customizer)](#apidoc.element.grunt.util._.setWith)
- description and source-code
```javascript
function setWith(object, path, value, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return object == null ? object : baseSet(object, path, value, customizer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.shuffle"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>shuffle (collection)](#apidoc.element.grunt.util._.shuffle)
- description and source-code
```javascript
function shuffle(collection) {
  return sampleSize(collection, MAX_ARRAY_LENGTH);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.size"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>size (collection)](#apidoc.element.grunt.util._.size)
- description and source-code
```javascript
function size(collection) {
  if (collection == null) {
    return 0;
  }
  if (isArrayLike(collection)) {
    var result = collection.length;
    return (result && isString(collection)) ? stringSize(collection) : result;
  }
  return keys(collection).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.slice"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>slice (array, start, end)](#apidoc.element.grunt.util._.slice)
- description and source-code
```javascript
function slice(array, start, end) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (end && typeof end != 'number' && isIterateeCall(array, start, end)) {
    start = 0;
    end = length;
  }
  else {
    start = start == null ? 0 : toInteger(start);
    end = end === undefined ? length : toInteger(end);
  }
  return baseSlice(array, start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.slugify"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>slugify (str)](#apidoc.element.grunt.util._.slugify)
- description and source-code
```javascript
function slugify(str) {
  return trim(dasherize(cleanDiacritics(str).replace(/[^\w\s-]/g, '-').toLowerCase()), '-');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.snakeCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>snakeCase (string)](#apidoc.element.grunt.util._.snakeCase)
- description and source-code
```javascript
snakeCase = function (string) {
  return arrayReduce(words(deburr(string)), callback, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.some"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>some (collection, predicate, guard)](#apidoc.element.grunt.util._.some)
- description and source-code
```javascript
function some(collection, predicate, guard) {
  var func = isArray(collection) ? arraySome : baseSome;
  if (guard && isIterateeCall(collection, predicate, guard)) {
    predicate = undefined;
  }
  return func(collection, getIteratee(predicate, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortBy ()](#apidoc.element.grunt.util._.sortBy)
- description and source-code
```javascript
sortBy = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortedIndex"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortedIndex (array, value)](#apidoc.element.grunt.util._.sortedIndex)
- description and source-code
```javascript
function sortedIndex(array, value) {
  return baseSortedIndex(array, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortedIndexBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortedIndexBy (array, value, iteratee)](#apidoc.element.grunt.util._.sortedIndexBy)
- description and source-code
```javascript
function sortedIndexBy(array, value, iteratee) {
  return baseSortedIndexBy(array, value, getIteratee(iteratee));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortedIndexOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortedIndexOf (array, value)](#apidoc.element.grunt.util._.sortedIndexOf)
- description and source-code
```javascript
function sortedIndexOf(array, value) {
  var length = array ? array.length : 0;
  if (length) {
    var index = baseSortedIndex(array, value);
    if (index < length && eq(array[index], value)) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortedLastIndex"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortedLastIndex (array, value)](#apidoc.element.grunt.util._.sortedLastIndex)
- description and source-code
```javascript
function sortedLastIndex(array, value) {
  return baseSortedIndex(array, value, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortedLastIndexBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortedLastIndexBy (array, value, iteratee)](#apidoc.element.grunt.util._.sortedLastIndexBy)
- description and source-code
```javascript
function sortedLastIndexBy(array, value, iteratee) {
  return baseSortedIndexBy(array, value, getIteratee(iteratee), true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortedLastIndexOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortedLastIndexOf (array, value)](#apidoc.element.grunt.util._.sortedLastIndexOf)
- description and source-code
```javascript
function sortedLastIndexOf(array, value) {
  var length = array ? array.length : 0;
  if (length) {
    var index = baseSortedIndex(array, value, true) - 1;
    if (eq(array[index], value)) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortedUniq"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortedUniq (array)](#apidoc.element.grunt.util._.sortedUniq)
- description and source-code
```javascript
function sortedUniq(array) {
  return (array && array.length)
    ? baseSortedUniq(array)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sortedUniqBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sortedUniqBy (array, iteratee)](#apidoc.element.grunt.util._.sortedUniqBy)
- description and source-code
```javascript
function sortedUniqBy(array, iteratee) {
  return (array && array.length)
    ? baseSortedUniqBy(array, getIteratee(iteratee))
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.splice"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>splice (str, i, howmany, substr)](#apidoc.element.grunt.util._.splice)
- description and source-code
```javascript
function splice(str, i, howmany, substr) {
  var arr = chars(str);
  arr.splice(~~i, ~~howmany, substr);
  return arr.join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.split"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>split (string, separator, limit)](#apidoc.element.grunt.util._.split)
- description and source-code
```javascript
function split(string, separator, limit) {
  return toString(string).split(separator, limit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.spread"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>spread (func, start)](#apidoc.element.grunt.util._.spread)
- description and source-code
```javascript
function spread(func, start) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  start = start === undefined ? 0 : nativeMax(toInteger(start), 0);
  return rest(function(args) {
    var array = args[start],
        otherArgs = args.slice(0, start);

    if (array) {
      arrayPush(otherArgs, array);
    }
    return apply(func, this, otherArgs);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sprintf"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sprintf ()](#apidoc.element.grunt.util._.sprintf)
- description and source-code
```javascript
sprintf = function () {
  if (!str_format.cache.hasOwnProperty(arguments[0])) {
    str_format.cache[arguments[0]] = str_format.parse(arguments[0]);
  }
  return str_format.format.call(null, str_format.cache[arguments[0]], arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.startCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>startCase (string)](#apidoc.element.grunt.util._.startCase)
- description and source-code
```javascript
startCase = function (string) {
  return arrayReduce(words(deburr(string)), callback, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.startsWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>startsWith (str, starts, position)](#apidoc.element.grunt.util._.startsWith)
- description and source-code
```javascript
function startsWith(str, starts, position) {
  str = makeString(str);
  starts = '' + starts;
  position = position == null ? 0 : Math.min(toPositive(position), str.length);
  return str.lastIndexOf(starts, position) === position;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>str (value)](#apidoc.element.grunt.util._.str)
- description and source-code
```javascript
function s(value) {
<span class="apidocCodeCommentSpan">  /* jshint validthis: true */
</span>  if (!(this instanceof s)) return new s(value);
  this._wrapped = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.strLeft"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>strLeft (str, sep)](#apidoc.element.grunt.util._.strLeft)
- description and source-code
```javascript
function strLeft(str, sep) {
  str = makeString(str);
  sep = makeString(sep);
  var pos = !sep ? -1 : str.indexOf(sep);
  return~ pos ? str.slice(0, pos) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.strLeftBack"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>strLeftBack (str, sep)](#apidoc.element.grunt.util._.strLeftBack)
- description and source-code
```javascript
function strLeftBack(str, sep) {
  str = makeString(str);
  sep = makeString(sep);
  var pos = str.lastIndexOf(sep);
  return~ pos ? str.slice(0, pos) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.strRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>strRight (str, sep)](#apidoc.element.grunt.util._.strRight)
- description and source-code
```javascript
function strRight(str, sep) {
  str = makeString(str);
  sep = makeString(sep);
  var pos = !sep ? -1 : str.indexOf(sep);
  return~ pos ? str.slice(pos + sep.length, str.length) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.strRightBack"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>strRightBack (str, sep)](#apidoc.element.grunt.util._.strRightBack)
- description and source-code
```javascript
function strRightBack(str, sep) {
  str = makeString(str);
  sep = makeString(sep);
  var pos = !sep ? -1 : str.lastIndexOf(sep);
  return~ pos ? str.slice(pos + sep.length, str.length) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.strip"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>strip (str, characters)](#apidoc.element.grunt.util._.strip)
- description and source-code
```javascript
function trim(str, characters) {
  str = makeString(str);
  if (!characters && nativeTrim) return nativeTrim.call(str);
  characters = defaultToWhiteSpace(characters);
  return str.replace(new RegExp('^' + characters + '+|' + characters + '+$', 'g'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.stripTags"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>stripTags (str)](#apidoc.element.grunt.util._.stripTags)
- description and source-code
```javascript
function stripTags(str) {
  return makeString(str).replace(/<\/?[^>]+>/g, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.subtract"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>subtract (minuend, subtrahend)](#apidoc.element.grunt.util._.subtract)
- description and source-code
```javascript
function subtract(minuend, subtrahend) {
  var result;
  if (minuend === undefined && subtrahend === undefined) {
    return 0;
  }
  if (minuend !== undefined) {
    result = minuend;
  }
  if (subtrahend !== undefined) {
    result = result === undefined ? subtrahend : (result - subtrahend);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.succ"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>succ (str)](#apidoc.element.grunt.util._.succ)
- description and source-code
```javascript
function succ(str) {
  return adjacent(str, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sum"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sum (array)](#apidoc.element.grunt.util._.sum)
- description and source-code
```javascript
function sum(array) {
  return (array && array.length)
    ? baseSum(array, identity)
    : 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.sumBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>sumBy (array, iteratee)](#apidoc.element.grunt.util._.sumBy)
- description and source-code
```javascript
function sumBy(array, iteratee) {
  return (array && array.length)
    ? baseSum(array, getIteratee(iteratee))
    : 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.surround"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>surround (str, wrapper)](#apidoc.element.grunt.util._.surround)
- description and source-code
```javascript
function surround(str, wrapper) {
  return [wrapper, str, wrapper].join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.swapCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>swapCase (str)](#apidoc.element.grunt.util._.swapCase)
- description and source-code
```javascript
function swapCase(str) {
  return makeString(str).replace(/\S/g, function(c) {
    return c === c.toUpperCase() ? c.toLowerCase() : c.toUpperCase();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.tail"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>tail (array)](#apidoc.element.grunt.util._.tail)
- description and source-code
```javascript
function tail(array) {
  return drop(array, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.take"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>take (array, n, guard)](#apidoc.element.grunt.util._.take)
- description and source-code
```javascript
function take(array, n, guard) {
  if (!(array && array.length)) {
    return [];
  }
  n = (guard || n === undefined) ? 1 : toInteger(n);
  return baseSlice(array, 0, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.takeRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>takeRight (array, n, guard)](#apidoc.element.grunt.util._.takeRight)
- description and source-code
```javascript
function takeRight(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  n = (guard || n === undefined) ? 1 : toInteger(n);
  n = length - n;
  return baseSlice(array, n < 0 ? 0 : n, length);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.takeRightWhile"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>takeRightWhile (array, predicate)](#apidoc.element.grunt.util._.takeRightWhile)
- description and source-code
```javascript
function takeRightWhile(array, predicate) {
  return (array && array.length)
    ? baseWhile(array, getIteratee(predicate, 3), false, true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.takeWhile"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>takeWhile (array, predicate)](#apidoc.element.grunt.util._.takeWhile)
- description and source-code
```javascript
function takeWhile(array, predicate) {
  return (array && array.length)
    ? baseWhile(array, getIteratee(predicate, 3))
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.tap"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>tap (value, interceptor)](#apidoc.element.grunt.util._.tap)
- description and source-code
```javascript
function tap(value, interceptor) {
  interceptor(value);
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.template"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>template (string, options, guard)](#apidoc.element.grunt.util._.template)
- description and source-code
```javascript
function template(string, options, guard) {
  // Based on John Resig's 'tmpl' implementation (http://ejohn.org/blog/javascript-micro-templating/)
  // and Laura Doktorova's doT.js (https://github.com/olado/doT).
  var settings = lodash.templateSettings;

  if (guard && isIterateeCall(string, options, guard)) {
    options = undefined;
  }
  string = toString(string);
  options = assignInWith({}, options, settings, assignInDefaults);

  var imports = assignInWith({}, options.imports, settings.imports, assignInDefaults),
      importsKeys = keys(imports),
      importsValues = baseValues(imports, importsKeys);

  var isEscaping,
      isEvaluating,
      index = 0,
      interpolate = options.interpolate || reNoMatch,
      source = "__p += '";

  // Compile the regexp to match each delimiter.
  var reDelimiters = RegExp(
    (options.escape || reNoMatch).source + '|' +
    interpolate.source + '|' +
    (interpolate === reInterpolate ? reEsTemplate : reNoMatch).source + '|' +
    (options.evaluate || reNoMatch).source + '|$'
  , 'g');

  // Use a sourceURL for easier debugging.
  var sourceURL = '//# sourceURL=' +
    ('sourceURL' in options
      ? options.sourceURL
      : ('lodash.templateSources[' + (++templateCounter) + ']')
    ) + '\n';

  string.replace(reDelimiters, function(match, escapeValue, interpolateValue, esTemplateValue, evaluateValue, offset) {
    interpolateValue || (interpolateValue = esTemplateValue);

    // Escape characters that can't be included in string literals.
    source += string.slice(index, offset).replace(reUnescapedString, escapeStringChar);

    // Replace delimiters with snippets.
    if (escapeValue) {
      isEscaping = true;
      source += "' +\n__e(" + escapeValue + ") +\n'";
    }
    if (evaluateValue) {
      isEvaluating = true;
      source += "';\n" + evaluateValue + ";\n__p += '";
    }
    if (interpolateValue) {
      source += "' +\n((__t = (" + interpolateValue + ")) == null ? '' : __t) +\n'";
    }
    index = offset + match.length;

    // The JS engine embedded in Adobe products needs 'match' returned in
    // order to produce the correct 'offset' value.
    return match;
  });

  source += "';\n";

  // If 'variable' is not specified wrap a with-statement around the generated
  // code to add the data object to the top of the scope chain.
  var variable = options.variable;
  if (!variable) {
    source = 'with (obj) {\n' + source + '\n}\n';
  }
  // Cleanup code by stripping empty strings.
  source = (isEvaluating ? source.replace(reEmptyStringLeading, '') : source)
    .replace(reEmptyStringMiddle, '$1')
    .replace(reEmptyStringTrailing, '$1;');

  // Frame code as the function body.
  source = 'function(' + (variable || 'obj') + ') {\n' +
    (variable
      ? ''
      : 'obj || (obj = {});\n'
    ) +
    "var __t, __p = ''" +
    (isEscaping
       ? ', __e = _.escape'
       : ''
    ) +
    (isEvaluating
      ? ', __j = Array.prototype.join;\n' +
        "function print() { __p += __j.call(arguments, '') }\n"
      : ';\n'
    ) +
    source +
    'return __p\n}';

  var result = attempt(function() {
    return Function(importsKeys, sourceURL + 'return ' + source).apply(undefined, importsValues);
  });

  // Provide the compiled function's source by its 'toString' method or
  // the 'source' property as a convenience for inlining compiled templates.
  result.source = source;
  if (isError(result)) {
    throw result;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.throttle"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>throttle (func, wait, options)](#apidoc.element.grunt.util._.throttle)
- description and source-code
```javascript
function throttle(func, wait, options) {
  var leading = true,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  if (isObject(options)) {
    leading = 'leading' in options ? !!options.leading : leading;
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }
  return debounce(func, wait, { 'leading': leading, 'maxWait': wait, 'trailing': trailing });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.thru"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>thru (value, interceptor)](#apidoc.element.grunt.util._.thru)
- description and source-code
```javascript
function thru(value, interceptor) {
  return interceptor(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.times"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>times (n, iteratee)](#apidoc.element.grunt.util._.times)
- description and source-code
```javascript
function times(n, iteratee) {
  n = toInteger(n);
  if (n < 1 || n > MAX_SAFE_INTEGER) {
    return [];
  }
  var index = MAX_ARRAY_LENGTH,
      length = nativeMin(n, MAX_ARRAY_LENGTH);

  iteratee = toFunction(iteratee);
  n -= MAX_ARRAY_LENGTH;

  var result = baseTimes(length, iteratee);
  while (++index < n) {
    iteratee(index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.titleize"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>titleize (str)](#apidoc.element.grunt.util._.titleize)
- description and source-code
```javascript
function titleize(str) {
  return makeString(str).toLowerCase().replace(/(?:^|\s|-)\S/g, function(c) {
    return c.toUpperCase();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toArray"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toArray (value)](#apidoc.element.grunt.util._.toArray)
- description and source-code
```javascript
function toArray(value) {
  if (!value) {
    return [];
  }
  if (isArrayLike(value)) {
    return isString(value) ? stringToArray(value) : copyArray(value);
  }
  if (iteratorSymbol && value[iteratorSymbol]) {
    return iteratorToArray(value[iteratorSymbol]());
  }
  var tag = getTag(value),
      func = tag == mapTag ? mapToArray : (tag == setTag ? setToArray : values);

  return func(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toBool"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toBool (str, trueValues, falseValues)](#apidoc.element.grunt.util._.toBool)
- description and source-code
```javascript
function toBoolean(str, trueValues, falseValues) {
  if (typeof str === "number") str = "" + str;
  if (typeof str !== "string") return !!str;
  str = trim(str);
  if (boolMatch(str, trueValues || ["true", "1"])) return true;
  if (boolMatch(str, falseValues || ["false", "0"])) return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toBoolean"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toBoolean (str, trueValues, falseValues)](#apidoc.element.grunt.util._.toBoolean)
- description and source-code
```javascript
function toBoolean(str, trueValues, falseValues) {
  if (typeof str === "number") str = "" + str;
  if (typeof str !== "string") return !!str;
  str = trim(str);
  if (boolMatch(str, trueValues || ["true", "1"])) return true;
  if (boolMatch(str, falseValues || ["false", "0"])) return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toInteger"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toInteger (value)](#apidoc.element.grunt.util._.toInteger)
- description and source-code
```javascript
function toInteger(value) {
  if (!value) {
    return value === 0 ? value : 0;
  }
  value = toNumber(value);
  if (value === INFINITY || value === -INFINITY) {
    var sign = (value < 0 ? -1 : 1);
    return sign * MAX_INTEGER;
  }
  var remainder = value % 1;
  return value === value ? (remainder ? value - remainder : value) : 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toLength"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toLength (value)](#apidoc.element.grunt.util._.toLength)
- description and source-code
```javascript
function toLength(value) {
  return value ? baseClamp(toInteger(value), 0, MAX_ARRAY_LENGTH) : 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toLower"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toLower (value)](#apidoc.element.grunt.util._.toLower)
- description and source-code
```javascript
function toLower(value) {
  return toString(value).toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toNumber"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toNumber (num, precision)](#apidoc.element.grunt.util._.toNumber)
- description and source-code
```javascript
function toNumber(num, precision) {
  if (num == null) return 0;
  var factor = Math.pow(10, isFinite(precision) ? precision : 0);
  return Math.round(num * factor) / factor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toPairs"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toPairs (object)](#apidoc.element.grunt.util._.toPairs)
- description and source-code
```javascript
function toPairs(object) {
  return baseToPairs(object, keys(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toPairsIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toPairsIn (object)](#apidoc.element.grunt.util._.toPairsIn)
- description and source-code
```javascript
function toPairsIn(object) {
  return baseToPairs(object, keysIn(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toPath"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toPath (value)](#apidoc.element.grunt.util._.toPath)
- description and source-code
```javascript
function toPath(value) {
  return isArray(value) ? arrayMap(value, String) : stringToPath(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toPlainObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toPlainObject (value)](#apidoc.element.grunt.util._.toPlainObject)
- description and source-code
```javascript
function toPlainObject(value) {
  return copyObject(value, keysIn(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toSafeInteger"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toSafeInteger (value)](#apidoc.element.grunt.util._.toSafeInteger)
- description and source-code
```javascript
function toSafeInteger(value) {
  return baseClamp(toInteger(value), -MAX_SAFE_INTEGER, MAX_SAFE_INTEGER);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toSentence"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toSentence (array, separator, lastSeparator, serial)](#apidoc.element.grunt.util._.toSentence)
- description and source-code
```javascript
function toSentence(array, separator, lastSeparator, serial) {
  separator = separator || ', ';
  lastSeparator = lastSeparator || ' and ';
  var a = array.slice(),
    lastMember = a.pop();

  if (array.length > 2 && serial) lastSeparator = rtrim(separator) + lastSeparator;

  return a.length ? a.join(separator) + lastSeparator + lastMember : lastMember;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toSentenceSerial"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toSentenceSerial (array, sep, lastSep)](#apidoc.element.grunt.util._.toSentenceSerial)
- description and source-code
```javascript
function toSentenceSerial(array, sep, lastSep) {
  return toSentence(array, sep, lastSep, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toString"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toString (value)](#apidoc.element.grunt.util._.toString)
- description and source-code
```javascript
function toString(value) {
  // Exit early for strings to avoid a performance hit in some environments.
  if (typeof value == 'string') {
    return value;
  }
  if (value == null) {
    return '';
  }
  if (isSymbol(value)) {
    return Symbol ? symbolToString.call(value) : '';
  }
  var result = (value + '');
  return (result == '0' && (1 / value) == -INFINITY) ? '-0' : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.toUpper"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>toUpper (value)](#apidoc.element.grunt.util._.toUpper)
- description and source-code
```javascript
function toUpper(value) {
  return toString(value).toUpperCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.transform"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>transform (object, iteratee, accumulator)](#apidoc.element.grunt.util._.transform)
- description and source-code
```javascript
function transform(object, iteratee, accumulator) {
  var isArr = isArray(object) || isTypedArray(object);
  iteratee = getIteratee(iteratee, 4);

  if (accumulator == null) {
    if (isArr || isObject(object)) {
      var Ctor = object.constructor;
      if (isArr) {
        accumulator = isArray(object) ? new Ctor : [];
      } else {
        accumulator = baseCreate(isFunction(Ctor) ? Ctor.prototype : undefined);
      }
    } else {
      accumulator = {};
    }
  }
  (isArr ? arrayEach : baseForOwn)(object, function(value, index, object) {
    return iteratee(accumulator, value, index, object);
  });
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.trim"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>trim (str, characters)](#apidoc.element.grunt.util._.trim)
- description and source-code
```javascript
function trim(str, characters) {
  str = makeString(str);
  if (!characters && nativeTrim) return nativeTrim.call(str);
  characters = defaultToWhiteSpace(characters);
  return str.replace(new RegExp('^' + characters + '+|' + characters + '+$', 'g'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.trimEnd"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>trimEnd (string, chars, guard)](#apidoc.element.grunt.util._.trimEnd)
- description and source-code
```javascript
function trimEnd(string, chars, guard) {
  string = toString(string);
  if (!string) {
    return string;
  }
  if (guard || chars === undefined) {
    return string.replace(reTrimEnd, '');
  }
  chars = (chars + '');
  if (!chars) {
    return string;
  }
  var strSymbols = stringToArray(string);
  return strSymbols.slice(0, charsEndIndex(strSymbols, stringToArray(chars)) + 1).join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.trimStart"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>trimStart (string, chars, guard)](#apidoc.element.grunt.util._.trimStart)
- description and source-code
```javascript
function trimStart(string, chars, guard) {
  string = toString(string);
  if (!string) {
    return string;
  }
  if (guard || chars === undefined) {
    return string.replace(reTrimStart, '');
  }
  chars = (chars + '');
  if (!chars) {
    return string;
  }
  var strSymbols = stringToArray(string);
  return strSymbols.slice(charsStartIndex(strSymbols, stringToArray(chars))).join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.truncate"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>truncate (str, length, truncateStr)](#apidoc.element.grunt.util._.truncate)
- description and source-code
```javascript
function truncate(str, length, truncateStr) {
  str = makeString(str);
  truncateStr = truncateStr || '...';
  length = ~~length;
  return str.length > length ? str.slice(0, length) + truncateStr : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unary"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unary (func)](#apidoc.element.grunt.util._.unary)
- description and source-code
```javascript
function unary(func) {
  return ary(func, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.underscored"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>underscored (str)](#apidoc.element.grunt.util._.underscored)
- description and source-code
```javascript
function underscored(str) {
  return trim(str).replace(/([a-z\d])([A-Z]+)/g, '$1_$2').replace(/[-\s]+/g, '_').toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unescape"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unescape (string)](#apidoc.element.grunt.util._.unescape)
- description and source-code
```javascript
function unescape(string) {
  string = toString(string);
  return (string && reHasEscapedHtml.test(string))
    ? string.replace(reEscapedHtml, unescapeHtmlChar)
    : string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unescapeHTML"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unescapeHTML (str)](#apidoc.element.grunt.util._.unescapeHTML)
- description and source-code
```javascript
function unescapeHTML(str) {
  return makeString(str).replace(/\&([^;]+);/g, function(entity, entityCode) {
    var match;

    if (entityCode in htmlEntities) {
      return htmlEntities[entityCode];
<span class="apidocCodeCommentSpan">    /*eslint no-cond-assign: 0*/
</span>    } else if (match = entityCode.match(/^#x([\da-fA-F]+)$/)) {
      return String.fromCharCode(parseInt(match[1], 16));
    /*eslint no-cond-assign: 0*/
    } else if (match = entityCode.match(/^#(\d+)$/)) {
      return String.fromCharCode(~~match[1]);
    } else {
      return entity;
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.union"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>union ()](#apidoc.element.grunt.util._.union)
- description and source-code
```javascript
union = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unionBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unionBy ()](#apidoc.element.grunt.util._.unionBy)
- description and source-code
```javascript
unionBy = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unionWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unionWith ()](#apidoc.element.grunt.util._.unionWith)
- description and source-code
```javascript
unionWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.uniq"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>uniq (array)](#apidoc.element.grunt.util._.uniq)
- description and source-code
```javascript
function uniq(array) {
  return (array && array.length)
    ? baseUniq(array)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.uniqBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>uniqBy (array, iteratee)](#apidoc.element.grunt.util._.uniqBy)
- description and source-code
```javascript
function uniqBy(array, iteratee) {
  return (array && array.length)
    ? baseUniq(array, getIteratee(iteratee))
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.uniqWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>uniqWith (array, comparator)](#apidoc.element.grunt.util._.uniqWith)
- description and source-code
```javascript
function uniqWith(array, comparator) {
  return (array && array.length)
    ? baseUniq(array, undefined, comparator)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.uniqueId"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>uniqueId (prefix)](#apidoc.element.grunt.util._.uniqueId)
- description and source-code
```javascript
function uniqueId(prefix) {
  var id = ++idCounter;
  return toString(prefix) + id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unquote"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unquote (str, quoteChar)](#apidoc.element.grunt.util._.unquote)
- description and source-code
```javascript
function unquote(str, quoteChar) {
  quoteChar = quoteChar || '"';
  if (str[0] === quoteChar && str[str.length - 1] === quoteChar)
    return str.slice(1, str.length - 1);
  else return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unset"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unset (object, path)](#apidoc.element.grunt.util._.unset)
- description and source-code
```javascript
function unset(object, path) {
  return object == null ? true : baseUnset(object, path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unzip"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unzip (array)](#apidoc.element.grunt.util._.unzip)
- description and source-code
```javascript
function unzip(array) {
  if (!(array && array.length)) {
    return [];
  }
  var length = 0;
  array = arrayFilter(array, function(group) {
    if (isArrayLikeObject(group)) {
      length = nativeMax(group.length, length);
      return true;
    }
  });
  return baseTimes(length, function(index) {
    return arrayMap(array, baseProperty(index));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.unzipWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>unzipWith (array, iteratee)](#apidoc.element.grunt.util._.unzipWith)
- description and source-code
```javascript
function unzipWith(array, iteratee) {
  if (!(array && array.length)) {
    return [];
  }
  var result = unzip(array);
  if (iteratee == null) {
    return result;
  }
  return arrayMap(result, function(group) {
    return apply(iteratee, undefined, group);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.upperCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>upperCase (string)](#apidoc.element.grunt.util._.upperCase)
- description and source-code
```javascript
upperCase = function (string) {
  return arrayReduce(words(deburr(string)), callback, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.upperFirst"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>upperFirst (string)](#apidoc.element.grunt.util._.upperFirst)
- description and source-code
```javascript
upperFirst = function (string) {
  string = toString(string);

  var strSymbols = reHasComplexSymbol.test(string) ? stringToArray(string) : undefined,
      chr = strSymbols ? strSymbols[0] : string.charAt(0),
      trailing = strSymbols ? strSymbols.slice(1).join('') : string.slice(1);

  return chr[methodName]() + trailing;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.values"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>values (object)](#apidoc.element.grunt.util._.values)
- description and source-code
```javascript
function values(object) {
  return object ? baseValues(object, keys(object)) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.valuesIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>valuesIn (object)](#apidoc.element.grunt.util._.valuesIn)
- description and source-code
```javascript
function valuesIn(object) {
  return object == null ? baseValues(object, keysIn(object)) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.vsprintf"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>vsprintf (fmt, argv)](#apidoc.element.grunt.util._.vsprintf)
- description and source-code
```javascript
function vsprintf(fmt, argv) {
  argv.unshift(fmt);
  return sprintf.apply(null, argv);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.without"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>without ()](#apidoc.element.grunt.util._.without)
- description and source-code
```javascript
without = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.words"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>words (str, delimiter)](#apidoc.element.grunt.util._.words)
- description and source-code
```javascript
function words(str, delimiter) {
  if (isBlank(str)) return [];
  return trim(str, delimiter).split(delimiter || /\s+/);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.wrap"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>wrap (str, options)](#apidoc.element.grunt.util._.wrap)
- description and source-code
```javascript
function wrap(str, options){
	str = makeString(str);

	options = options || {};

	var width = options.width || 75;
	var seperator = options.seperator || '\n';
	var cut = options.cut || false;
	var preserveSpaces = options.preserveSpaces || false;
	var trailingSpaces = options.trailingSpaces || false;

  var result;

	if(width <= 0){
		return str;
	}

	else if(!cut){

		var words = str.split(" ");
		var current_column = 0;
		result = "";

		while(words.length > 0){
			
			// if adding a space and the next word would cause this line to be longer than width...
			if(1 + words[0].length + current_column > width){
				//start a new line if this line is not already empty
				if(current_column > 0){
					// add a space at the end of the line is preserveSpaces is true
					if (preserveSpaces){
						result += ' ';
						current_column++;
					}
					// fill the rest of the line with spaces if trailingSpaces option is true
					else if(trailingSpaces){
						while(current_column < width){
							result += ' ';
							current_column++;
						}						
					}
					//start new line
					result += seperator;
					current_column = 0;
				}
			}

			// if not at the begining of the line, add a space in front of the word
			if(current_column > 0){
				result += " ";
				current_column++;
			}

			// tack on the next word, update current column, a pop words array
			result += words[0];
			current_column += words[0].length;
			words.shift();

		}

		// fill the rest of the line with spaces if trailingSpaces option is true
		if(trailingSpaces){
			while(current_column < width){
				result += ' ';
				current_column++;
			}						
		}

		return result;

	}

	else {

		var index = 0;
		result = "";

		// walk through each character and add seperators where appropriate
		while(index < str.length){
			if(index % width == 0 && index > 0){
				result += seperator;
			}
			result += str.charAt(index);
			index++;
		}

		// fill the rest of the line with spaces if trailingSpaces option is true
		if(trailingSpaces){
			while(index % width > 0){
				result += ' ';
				index++;
			}						
		}
		
		return result;
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.xor"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>xor ()](#apidoc.element.grunt.util._.xor)
- description and source-code
```javascript
xor = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.xorBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>xorBy ()](#apidoc.element.grunt.util._.xorBy)
- description and source-code
```javascript
xorBy = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.xorWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>xorWith ()](#apidoc.element.grunt.util._.xorWith)
- description and source-code
```javascript
xorWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.zip"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>zip ()](#apidoc.element.grunt.util._.zip)
- description and source-code
```javascript
zip = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.zipObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>zipObject (props, values)](#apidoc.element.grunt.util._.zipObject)
- description and source-code
```javascript
function zipObject(props, values) {
  return baseZipObject(props || [], values || [], assignValue);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.zipObjectDeep"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>zipObjectDeep (props, values)](#apidoc.element.grunt.util._.zipObjectDeep)
- description and source-code
```javascript
function zipObjectDeep(props, values) {
  return baseZipObject(props || [], values || [], baseSet);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.zipWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.</span>zipWith ()](#apidoc.element.grunt.util._.zipWith)
- description and source-code
```javascript
zipWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util._.prototype"></a>[module grunt.util._.prototype](#apidoc.module.grunt.util._.prototype)

#### <a name="apidoc.element.grunt.util._.prototype.add"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>add ()](#apidoc.element.grunt.util._.prototype.add)
- description and source-code
```javascript
add = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.after"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>after ()](#apidoc.element.grunt.util._.prototype.after)
- description and source-code
```javascript
after = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.ary"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>ary ()](#apidoc.element.grunt.util._.prototype.ary)
- description and source-code
```javascript
ary = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.assign"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>assign ()](#apidoc.element.grunt.util._.prototype.assign)
- description and source-code
```javascript
assign = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.assignIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>assignIn ()](#apidoc.element.grunt.util._.prototype.assignIn)
- description and source-code
```javascript
assignIn = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.assignInWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>assignInWith ()](#apidoc.element.grunt.util._.prototype.assignInWith)
- description and source-code
```javascript
assignInWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.assignWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>assignWith ()](#apidoc.element.grunt.util._.prototype.assignWith)
- description and source-code
```javascript
assignWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.at"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>at ()](#apidoc.element.grunt.util._.prototype.at)
- description and source-code
```javascript
at = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, array);
    case 1: return func.call(this, args[0], array);
    case 2: return func.call(this, args[0], args[1], array);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.attempt"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>attempt ()](#apidoc.element.grunt.util._.prototype.attempt)
- description and source-code
```javascript
attempt = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.before"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>before ()](#apidoc.element.grunt.util._.prototype.before)
- description and source-code
```javascript
before = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.bind"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>bind ()](#apidoc.element.grunt.util._.prototype.bind)
- description and source-code
```javascript
bind = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.bindAll"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>bindAll ()](#apidoc.element.grunt.util._.prototype.bindAll)
- description and source-code
```javascript
bindAll = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.bindKey"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>bindKey ()](#apidoc.element.grunt.util._.prototype.bindKey)
- description and source-code
```javascript
bindKey = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.camelCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>camelCase ()](#apidoc.element.grunt.util._.prototype.camelCase)
- description and source-code
```javascript
camelCase = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.camelcase"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>camelcase ()](#apidoc.element.grunt.util._.prototype.camelcase)
- description and source-code
```javascript
camelcase = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.camelize"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>camelize ()](#apidoc.element.grunt.util._.prototype.camelize)
- description and source-code
```javascript
camelize = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.capitalize"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>capitalize ()](#apidoc.element.grunt.util._.prototype.capitalize)
- description and source-code
```javascript
capitalize = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.ceil"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>ceil ()](#apidoc.element.grunt.util._.prototype.ceil)
- description and source-code
```javascript
ceil = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.center"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>center ()](#apidoc.element.grunt.util._.prototype.center)
- description and source-code
```javascript
center = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.chain"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>chain ()](#apidoc.element.grunt.util._.prototype.chain)
- description and source-code
```javascript
function wrapperChain() {
  return chain(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.chars"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>chars ()](#apidoc.element.grunt.util._.prototype.chars)
- description and source-code
```javascript
chars = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.chop"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>chop ()](#apidoc.element.grunt.util._.prototype.chop)
- description and source-code
```javascript
chop = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.chunk"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>chunk ()](#apidoc.element.grunt.util._.prototype.chunk)
- description and source-code
```javascript
chunk = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.clamp"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>clamp ()](#apidoc.element.grunt.util._.prototype.clamp)
- description and source-code
```javascript
clamp = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.classify"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>classify ()](#apidoc.element.grunt.util._.prototype.classify)
- description and source-code
```javascript
classify = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.clean"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>clean ()](#apidoc.element.grunt.util._.prototype.clean)
- description and source-code
```javascript
clean = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.cleanDiacritics"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cleanDiacritics ()](#apidoc.element.grunt.util._.prototype.cleanDiacritics)
- description and source-code
```javascript
cleanDiacritics = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.clone"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>clone ()](#apidoc.element.grunt.util._.prototype.clone)
- description and source-code
```javascript
clone = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.cloneDeep"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cloneDeep ()](#apidoc.element.grunt.util._.prototype.cloneDeep)
- description and source-code
```javascript
cloneDeep = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.cloneDeepWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cloneDeepWith ()](#apidoc.element.grunt.util._.prototype.cloneDeepWith)
- description and source-code
```javascript
cloneDeepWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.cloneWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cloneWith ()](#apidoc.element.grunt.util._.prototype.cloneWith)
- description and source-code
```javascript
cloneWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.commit"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>commit ()](#apidoc.element.grunt.util._.prototype.commit)
- description and source-code
```javascript
function wrapperCommit() {
  return new LodashWrapper(this.value(), this.__chain__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.compact"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>compact ()](#apidoc.element.grunt.util._.prototype.compact)
- description and source-code
```javascript
compact = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.concat"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>concat ()](#apidoc.element.grunt.util._.prototype.concat)
- description and source-code
```javascript
concat = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.cond"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>cond ()](#apidoc.element.grunt.util._.prototype.cond)
- description and source-code
```javascript
cond = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.conforms"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>conforms ()](#apidoc.element.grunt.util._.prototype.conforms)
- description and source-code
```javascript
conforms = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.constant"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>constant ()](#apidoc.element.grunt.util._.prototype.constant)
- description and source-code
```javascript
constant = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.count"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>count ()](#apidoc.element.grunt.util._.prototype.count)
- description and source-code
```javascript
count = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.countBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>countBy ()](#apidoc.element.grunt.util._.prototype.countBy)
- description and source-code
```javascript
countBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.create"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>create ()](#apidoc.element.grunt.util._.prototype.create)
- description and source-code
```javascript
create = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.curry"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>curry ()](#apidoc.element.grunt.util._.prototype.curry)
- description and source-code
```javascript
curry = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.curryRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>curryRight ()](#apidoc.element.grunt.util._.prototype.curryRight)
- description and source-code
```javascript
curryRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.dasherize"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dasherize ()](#apidoc.element.grunt.util._.prototype.dasherize)
- description and source-code
```javascript
dasherize = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.debounce"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>debounce ()](#apidoc.element.grunt.util._.prototype.debounce)
- description and source-code
```javascript
debounce = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.deburr"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>deburr ()](#apidoc.element.grunt.util._.prototype.deburr)
- description and source-code
```javascript
deburr = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.decapitalize"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>decapitalize ()](#apidoc.element.grunt.util._.prototype.decapitalize)
- description and source-code
```javascript
decapitalize = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.dedent"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dedent ()](#apidoc.element.grunt.util._.prototype.dedent)
- description and source-code
```javascript
dedent = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.defaults"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>defaults ()](#apidoc.element.grunt.util._.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.defaultsDeep"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>defaultsDeep ()](#apidoc.element.grunt.util._.prototype.defaultsDeep)
- description and source-code
```javascript
defaultsDeep = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.defer"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>defer ()](#apidoc.element.grunt.util._.prototype.defer)
- description and source-code
```javascript
defer = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.delay"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>delay ()](#apidoc.element.grunt.util._.prototype.delay)
- description and source-code
```javascript
delay = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.difference"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>difference ()](#apidoc.element.grunt.util._.prototype.difference)
- description and source-code
```javascript
difference = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.differenceBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>differenceBy ()](#apidoc.element.grunt.util._.prototype.differenceBy)
- description and source-code
```javascript
differenceBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.differenceWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>differenceWith ()](#apidoc.element.grunt.util._.prototype.differenceWith)
- description and source-code
```javascript
differenceWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.drop"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>drop ()](#apidoc.element.grunt.util._.prototype.drop)
- description and source-code
```javascript
drop = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.dropRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dropRight ()](#apidoc.element.grunt.util._.prototype.dropRight)
- description and source-code
```javascript
dropRight = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.dropRightWhile"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dropRightWhile ()](#apidoc.element.grunt.util._.prototype.dropRightWhile)
- description and source-code
```javascript
dropRightWhile = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.dropWhile"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>dropWhile ()](#apidoc.element.grunt.util._.prototype.dropWhile)
- description and source-code
```javascript
dropWhile = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.each"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>each ()](#apidoc.element.grunt.util._.prototype.each)
- description and source-code
```javascript
each = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.eachRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>eachRight ()](#apidoc.element.grunt.util._.prototype.eachRight)
- description and source-code
```javascript
eachRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.endsWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>endsWith ()](#apidoc.element.grunt.util._.prototype.endsWith)
- description and source-code
```javascript
endsWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.eq"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>eq ()](#apidoc.element.grunt.util._.prototype.eq)
- description and source-code
```javascript
eq = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.escape"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>escape ()](#apidoc.element.grunt.util._.prototype.escape)
- description and source-code
```javascript
escape = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.escapeHTML"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>escapeHTML ()](#apidoc.element.grunt.util._.prototype.escapeHTML)
- description and source-code
```javascript
escapeHTML = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.escapeRegExp"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>escapeRegExp ()](#apidoc.element.grunt.util._.prototype.escapeRegExp)
- description and source-code
```javascript
escapeRegExp = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.every"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>every ()](#apidoc.element.grunt.util._.prototype.every)
- description and source-code
```javascript
every = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.exports"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>exports ()](#apidoc.element.grunt.util._.prototype.exports)
- description and source-code
```javascript
exports = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.extend"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>extend ()](#apidoc.element.grunt.util._.prototype.extend)
- description and source-code
```javascript
extend = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.extendWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>extendWith ()](#apidoc.element.grunt.util._.prototype.extendWith)
- description and source-code
```javascript
extendWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.fill"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>fill ()](#apidoc.element.grunt.util._.prototype.fill)
- description and source-code
```javascript
fill = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.filter"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>filter ()](#apidoc.element.grunt.util._.prototype.filter)
- description and source-code
```javascript
filter = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.find"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>find ()](#apidoc.element.grunt.util._.prototype.find)
- description and source-code
```javascript
find = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.findIndex"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findIndex ()](#apidoc.element.grunt.util._.prototype.findIndex)
- description and source-code
```javascript
findIndex = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.findKey"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findKey ()](#apidoc.element.grunt.util._.prototype.findKey)
- description and source-code
```javascript
findKey = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.findLast"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findLast ()](#apidoc.element.grunt.util._.prototype.findLast)
- description and source-code
```javascript
findLast = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.findLastIndex"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findLastIndex ()](#apidoc.element.grunt.util._.prototype.findLastIndex)
- description and source-code
```javascript
findLastIndex = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.findLastKey"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>findLastKey ()](#apidoc.element.grunt.util._.prototype.findLastKey)
- description and source-code
```javascript
findLastKey = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.first"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>first ()](#apidoc.element.grunt.util._.prototype.first)
- description and source-code
```javascript
first = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.flatMap"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flatMap (iteratee)](#apidoc.element.grunt.util._.prototype.flatMap)
- description and source-code
```javascript
function wrapperFlatMap(iteratee) {
  return this.map(iteratee).flatten();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.flatten"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flatten ()](#apidoc.element.grunt.util._.prototype.flatten)
- description and source-code
```javascript
flatten = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.flattenDeep"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flattenDeep ()](#apidoc.element.grunt.util._.prototype.flattenDeep)
- description and source-code
```javascript
flattenDeep = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.flip"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flip ()](#apidoc.element.grunt.util._.prototype.flip)
- description and source-code
```javascript
flip = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.floor"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>floor ()](#apidoc.element.grunt.util._.prototype.floor)
- description and source-code
```javascript
floor = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.flow"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flow ()](#apidoc.element.grunt.util._.prototype.flow)
- description and source-code
```javascript
flow = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.flowRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>flowRight ()](#apidoc.element.grunt.util._.prototype.flowRight)
- description and source-code
```javascript
flowRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.forEach"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forEach ()](#apidoc.element.grunt.util._.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.forEachRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forEachRight ()](#apidoc.element.grunt.util._.prototype.forEachRight)
- description and source-code
```javascript
forEachRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.forIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forIn ()](#apidoc.element.grunt.util._.prototype.forIn)
- description and source-code
```javascript
forIn = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.forInRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forInRight ()](#apidoc.element.grunt.util._.prototype.forInRight)
- description and source-code
```javascript
forInRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.forOwn"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forOwn ()](#apidoc.element.grunt.util._.prototype.forOwn)
- description and source-code
```javascript
forOwn = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.forOwnRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>forOwnRight ()](#apidoc.element.grunt.util._.prototype.forOwnRight)
- description and source-code
```javascript
forOwnRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.fromPairs"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>fromPairs ()](#apidoc.element.grunt.util._.prototype.fromPairs)
- description and source-code
```javascript
fromPairs = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.functions"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>functions ()](#apidoc.element.grunt.util._.prototype.functions)
- description and source-code
```javascript
functions = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.functionsIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>functionsIn ()](#apidoc.element.grunt.util._.prototype.functionsIn)
- description and source-code
```javascript
functionsIn = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.get"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>get ()](#apidoc.element.grunt.util._.prototype.get)
- description and source-code
```javascript
get = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.groupBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>groupBy ()](#apidoc.element.grunt.util._.prototype.groupBy)
- description and source-code
```javascript
groupBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.gt"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>gt ()](#apidoc.element.grunt.util._.prototype.gt)
- description and source-code
```javascript
gt = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.gte"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>gte ()](#apidoc.element.grunt.util._.prototype.gte)
- description and source-code
```javascript
gte = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.has"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>has ()](#apidoc.element.grunt.util._.prototype.has)
- description and source-code
```javascript
has = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.hasIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>hasIn ()](#apidoc.element.grunt.util._.prototype.hasIn)
- description and source-code
```javascript
hasIn = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.head"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>head ()](#apidoc.element.grunt.util._.prototype.head)
- description and source-code
```javascript
head = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.humanize"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>humanize ()](#apidoc.element.grunt.util._.prototype.humanize)
- description and source-code
```javascript
humanize = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.identity"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>identity ()](#apidoc.element.grunt.util._.prototype.identity)
- description and source-code
```javascript
identity = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.inRange"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>inRange ()](#apidoc.element.grunt.util._.prototype.inRange)
- description and source-code
```javascript
inRange = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.includes"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>includes ()](#apidoc.element.grunt.util._.prototype.includes)
- description and source-code
```javascript
includes = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.indexOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>indexOf ()](#apidoc.element.grunt.util._.prototype.indexOf)
- description and source-code
```javascript
indexOf = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.initial"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>initial ()](#apidoc.element.grunt.util._.prototype.initial)
- description and source-code
```javascript
initial = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.insert"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>insert ()](#apidoc.element.grunt.util._.prototype.insert)
- description and source-code
```javascript
insert = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.intersection"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>intersection ()](#apidoc.element.grunt.util._.prototype.intersection)
- description and source-code
```javascript
intersection = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.intersectionBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>intersectionBy ()](#apidoc.element.grunt.util._.prototype.intersectionBy)
- description and source-code
```javascript
intersectionBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.intersectionWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>intersectionWith ()](#apidoc.element.grunt.util._.prototype.intersectionWith)
- description and source-code
```javascript
intersectionWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.invert"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>invert ()](#apidoc.element.grunt.util._.prototype.invert)
- description and source-code
```javascript
invert = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.invertBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>invertBy ()](#apidoc.element.grunt.util._.prototype.invertBy)
- description and source-code
```javascript
invertBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.invoke"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>invoke ()](#apidoc.element.grunt.util._.prototype.invoke)
- description and source-code
```javascript
invoke = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.invokeMap"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>invokeMap ()](#apidoc.element.grunt.util._.prototype.invokeMap)
- description and source-code
```javascript
invokeMap = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArguments ()](#apidoc.element.grunt.util._.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isArray"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArray ()](#apidoc.element.grunt.util._.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isArrayBuffer"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArrayBuffer ()](#apidoc.element.grunt.util._.prototype.isArrayBuffer)
- description and source-code
```javascript
isArrayBuffer = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isArrayLike"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArrayLike ()](#apidoc.element.grunt.util._.prototype.isArrayLike)
- description and source-code
```javascript
isArrayLike = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isArrayLikeObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isArrayLikeObject ()](#apidoc.element.grunt.util._.prototype.isArrayLikeObject)
- description and source-code
```javascript
isArrayLikeObject = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isBlank"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isBlank ()](#apidoc.element.grunt.util._.prototype.isBlank)
- description and source-code
```javascript
isBlank = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isBoolean ()](#apidoc.element.grunt.util._.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isBuffer"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isBuffer ()](#apidoc.element.grunt.util._.prototype.isBuffer)
- description and source-code
```javascript
isBuffer = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isDate"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isDate ()](#apidoc.element.grunt.util._.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isElement"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isElement ()](#apidoc.element.grunt.util._.prototype.isElement)
- description and source-code
```javascript
isElement = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isEmpty ()](#apidoc.element.grunt.util._.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isEqual ()](#apidoc.element.grunt.util._.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isEqualWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isEqualWith ()](#apidoc.element.grunt.util._.prototype.isEqualWith)
- description and source-code
```javascript
isEqualWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isError"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isError ()](#apidoc.element.grunt.util._.prototype.isError)
- description and source-code
```javascript
isError = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isFinite"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isFinite ()](#apidoc.element.grunt.util._.prototype.isFinite)
- description and source-code
```javascript
isFinite = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isFunction ()](#apidoc.element.grunt.util._.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isInteger"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isInteger ()](#apidoc.element.grunt.util._.prototype.isInteger)
- description and source-code
```javascript
isInteger = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isLength"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isLength ()](#apidoc.element.grunt.util._.prototype.isLength)
- description and source-code
```javascript
isLength = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isMap"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isMap ()](#apidoc.element.grunt.util._.prototype.isMap)
- description and source-code
```javascript
isMap = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isMatch"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isMatch ()](#apidoc.element.grunt.util._.prototype.isMatch)
- description and source-code
```javascript
isMatch = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isMatchWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isMatchWith ()](#apidoc.element.grunt.util._.prototype.isMatchWith)
- description and source-code
```javascript
isMatchWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isNaN"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNaN ()](#apidoc.element.grunt.util._.prototype.isNaN)
- description and source-code
```javascript
isNaN = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isNative"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNative ()](#apidoc.element.grunt.util._.prototype.isNative)
- description and source-code
```javascript
isNative = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isNil"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNil ()](#apidoc.element.grunt.util._.prototype.isNil)
- description and source-code
```javascript
isNil = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isNull"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNull ()](#apidoc.element.grunt.util._.prototype.isNull)
- description and source-code
```javascript
isNull = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isNumber ()](#apidoc.element.grunt.util._.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isObject ()](#apidoc.element.grunt.util._.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isObjectLike"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isObjectLike ()](#apidoc.element.grunt.util._.prototype.isObjectLike)
- description and source-code
```javascript
isObjectLike = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isPlainObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isPlainObject ()](#apidoc.element.grunt.util._.prototype.isPlainObject)
- description and source-code
```javascript
isPlainObject = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isRegExp ()](#apidoc.element.grunt.util._.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isSafeInteger"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isSafeInteger ()](#apidoc.element.grunt.util._.prototype.isSafeInteger)
- description and source-code
```javascript
isSafeInteger = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isSet"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isSet ()](#apidoc.element.grunt.util._.prototype.isSet)
- description and source-code
```javascript
isSet = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isString"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isString ()](#apidoc.element.grunt.util._.prototype.isString)
- description and source-code
```javascript
isString = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isSymbol"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isSymbol ()](#apidoc.element.grunt.util._.prototype.isSymbol)
- description and source-code
```javascript
isSymbol = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isTypedArray"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isTypedArray ()](#apidoc.element.grunt.util._.prototype.isTypedArray)
- description and source-code
```javascript
isTypedArray = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isUndefined"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isUndefined ()](#apidoc.element.grunt.util._.prototype.isUndefined)
- description and source-code
```javascript
isUndefined = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isWeakMap"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isWeakMap ()](#apidoc.element.grunt.util._.prototype.isWeakMap)
- description and source-code
```javascript
isWeakMap = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.isWeakSet"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>isWeakSet ()](#apidoc.element.grunt.util._.prototype.isWeakSet)
- description and source-code
```javascript
isWeakSet = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.iteratee"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>iteratee ()](#apidoc.element.grunt.util._.prototype.iteratee)
- description and source-code
```javascript
iteratee = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.join"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>join ()](#apidoc.element.grunt.util._.prototype.join)
- description and source-code
```javascript
join = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.kebabCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>kebabCase ()](#apidoc.element.grunt.util._.prototype.kebabCase)
- description and source-code
```javascript
kebabCase = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.keyBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>keyBy ()](#apidoc.element.grunt.util._.prototype.keyBy)
- description and source-code
```javascript
keyBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.keys"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>keys ()](#apidoc.element.grunt.util._.prototype.keys)
- description and source-code
```javascript
keys = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.keysIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>keysIn ()](#apidoc.element.grunt.util._.prototype.keysIn)
- description and source-code
```javascript
keysIn = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.last"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>last ()](#apidoc.element.grunt.util._.prototype.last)
- description and source-code
```javascript
last = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lastIndexOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lastIndexOf ()](#apidoc.element.grunt.util._.prototype.lastIndexOf)
- description and source-code
```javascript
lastIndexOf = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.levenshtein"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>levenshtein ()](#apidoc.element.grunt.util._.prototype.levenshtein)
- description and source-code
```javascript
levenshtein = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lines"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lines ()](#apidoc.element.grunt.util._.prototype.lines)
- description and source-code
```javascript
lines = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.ljust"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>ljust ()](#apidoc.element.grunt.util._.prototype.ljust)
- description and source-code
```javascript
ljust = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lowerCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lowerCase ()](#apidoc.element.grunt.util._.prototype.lowerCase)
- description and source-code
```javascript
lowerCase = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lowerFirst"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lowerFirst ()](#apidoc.element.grunt.util._.prototype.lowerFirst)
- description and source-code
```javascript
lowerFirst = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lpad ()](#apidoc.element.grunt.util._.prototype.lpad)
- description and source-code
```javascript
lpad = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lrpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lrpad ()](#apidoc.element.grunt.util._.prototype.lrpad)
- description and source-code
```javascript
lrpad = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lstrip"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lstrip ()](#apidoc.element.grunt.util._.prototype.lstrip)
- description and source-code
```javascript
lstrip = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lt"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lt ()](#apidoc.element.grunt.util._.prototype.lt)
- description and source-code
```javascript
lt = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.lte"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>lte ()](#apidoc.element.grunt.util._.prototype.lte)
- description and source-code
```javascript
lte = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.ltrim"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>ltrim ()](#apidoc.element.grunt.util._.prototype.ltrim)
- description and source-code
```javascript
ltrim = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.map"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>map ()](#apidoc.element.grunt.util._.prototype.map)
- description and source-code
```javascript
map = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.mapChars"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mapChars ()](#apidoc.element.grunt.util._.prototype.mapChars)
- description and source-code
```javascript
mapChars = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.mapKeys"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mapKeys ()](#apidoc.element.grunt.util._.prototype.mapKeys)
- description and source-code
```javascript
mapKeys = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.mapValues"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mapValues ()](#apidoc.element.grunt.util._.prototype.mapValues)
- description and source-code
```javascript
mapValues = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.matches"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>matches ()](#apidoc.element.grunt.util._.prototype.matches)
- description and source-code
```javascript
matches = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.matchesProperty"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>matchesProperty ()](#apidoc.element.grunt.util._.prototype.matchesProperty)
- description and source-code
```javascript
matchesProperty = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.max"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>max ()](#apidoc.element.grunt.util._.prototype.max)
- description and source-code
```javascript
max = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.maxBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>maxBy ()](#apidoc.element.grunt.util._.prototype.maxBy)
- description and source-code
```javascript
maxBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.mean"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mean ()](#apidoc.element.grunt.util._.prototype.mean)
- description and source-code
```javascript
mean = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.memoize"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>memoize ()](#apidoc.element.grunt.util._.prototype.memoize)
- description and source-code
```javascript
memoize = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.merge"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>merge ()](#apidoc.element.grunt.util._.prototype.merge)
- description and source-code
```javascript
merge = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.mergeWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mergeWith ()](#apidoc.element.grunt.util._.prototype.mergeWith)
- description and source-code
```javascript
mergeWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.method"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>method ()](#apidoc.element.grunt.util._.prototype.method)
- description and source-code
```javascript
method = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.methodOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>methodOf ()](#apidoc.element.grunt.util._.prototype.methodOf)
- description and source-code
```javascript
methodOf = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.min"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>min ()](#apidoc.element.grunt.util._.prototype.min)
- description and source-code
```javascript
min = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.minBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>minBy ()](#apidoc.element.grunt.util._.prototype.minBy)
- description and source-code
```javascript
minBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.mixin"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>mixin ()](#apidoc.element.grunt.util._.prototype.mixin)
- description and source-code
```javascript
mixin = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.naturalCmp"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>naturalCmp ()](#apidoc.element.grunt.util._.prototype.naturalCmp)
- description and source-code
```javascript
naturalCmp = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.negate"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>negate ()](#apidoc.element.grunt.util._.prototype.negate)
- description and source-code
```javascript
negate = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.next"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>next ()](#apidoc.element.grunt.util._.prototype.next)
- description and source-code
```javascript
function wrapperNext() {
  if (this.__values__ === undefined) {
    this.__values__ = toArray(this.value());
  }
  var done = this.__index__ >= this.__values__.length,
      value = done ? undefined : this.__values__[this.__index__++];

  return { 'done': done, 'value': value };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.noConflict"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>noConflict ()](#apidoc.element.grunt.util._.prototype.noConflict)
- description and source-code
```javascript
noConflict = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.noop"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>noop ()](#apidoc.element.grunt.util._.prototype.noop)
- description and source-code
```javascript
noop = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.now"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>now ()](#apidoc.element.grunt.util._.prototype.now)
- description and source-code
```javascript
now = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.nthArg"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>nthArg ()](#apidoc.element.grunt.util._.prototype.nthArg)
- description and source-code
```javascript
nthArg = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.numberFormat"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>numberFormat ()](#apidoc.element.grunt.util._.prototype.numberFormat)
- description and source-code
```javascript
numberFormat = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.omit"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>omit ()](#apidoc.element.grunt.util._.prototype.omit)
- description and source-code
```javascript
omit = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.omitBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>omitBy ()](#apidoc.element.grunt.util._.prototype.omitBy)
- description and source-code
```javascript
omitBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.once"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>once ()](#apidoc.element.grunt.util._.prototype.once)
- description and source-code
```javascript
once = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.orderBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>orderBy ()](#apidoc.element.grunt.util._.prototype.orderBy)
- description and source-code
```javascript
orderBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.over"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>over ()](#apidoc.element.grunt.util._.prototype.over)
- description and source-code
```javascript
over = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.overArgs"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>overArgs ()](#apidoc.element.grunt.util._.prototype.overArgs)
- description and source-code
```javascript
overArgs = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.overEvery"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>overEvery ()](#apidoc.element.grunt.util._.prototype.overEvery)
- description and source-code
```javascript
overEvery = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.overSome"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>overSome ()](#apidoc.element.grunt.util._.prototype.overSome)
- description and source-code
```javascript
overSome = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pad"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pad ()](#apidoc.element.grunt.util._.prototype.pad)
- description and source-code
```javascript
pad = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.padEnd"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>padEnd ()](#apidoc.element.grunt.util._.prototype.padEnd)
- description and source-code
```javascript
padEnd = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.padStart"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>padStart ()](#apidoc.element.grunt.util._.prototype.padStart)
- description and source-code
```javascript
padStart = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.parseInt"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>parseInt ()](#apidoc.element.grunt.util._.prototype.parseInt)
- description and source-code
```javascript
parseInt = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.partial"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>partial ()](#apidoc.element.grunt.util._.prototype.partial)
- description and source-code
```javascript
partial = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.partialRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>partialRight ()](#apidoc.element.grunt.util._.prototype.partialRight)
- description and source-code
```javascript
partialRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.partition"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>partition ()](#apidoc.element.grunt.util._.prototype.partition)
- description and source-code
```javascript
partition = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pick"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pick ()](#apidoc.element.grunt.util._.prototype.pick)
- description and source-code
```javascript
pick = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pickBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pickBy ()](#apidoc.element.grunt.util._.prototype.pickBy)
- description and source-code
```javascript
pickBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.plant"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>plant (value)](#apidoc.element.grunt.util._.prototype.plant)
- description and source-code
```javascript
function wrapperPlant(value) {
  var result,
      parent = this;

  while (parent instanceof baseLodash) {
    var clone = wrapperClone(parent);
    clone.__index__ = 0;
    clone.__values__ = undefined;
    if (result) {
      previous.__wrapped__ = clone;
    } else {
      result = clone;
    }
    var previous = clone;
    parent = parent.__wrapped__;
  }
  previous.__wrapped__ = value;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pop"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pop ()](#apidoc.element.grunt.util._.prototype.pop)
- description and source-code
```javascript
pop = function () {
  var args = arguments;
  if (retUnwrapped && !this.__chain__) {
    return func.apply(this.value(), args);
  }
  return this[chainName](function(value) {
    return func.apply(value, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pred"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pred ()](#apidoc.element.grunt.util._.prototype.pred)
- description and source-code
```javascript
pred = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.property"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>property ()](#apidoc.element.grunt.util._.prototype.property)
- description and source-code
```javascript
property = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.propertyOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>propertyOf ()](#apidoc.element.grunt.util._.prototype.propertyOf)
- description and source-code
```javascript
propertyOf = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.prune"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>prune ()](#apidoc.element.grunt.util._.prototype.prune)
- description and source-code
```javascript
prune = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pull"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pull ()](#apidoc.element.grunt.util._.prototype.pull)
- description and source-code
```javascript
pull = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pullAll"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pullAll ()](#apidoc.element.grunt.util._.prototype.pullAll)
- description and source-code
```javascript
pullAll = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pullAllBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pullAllBy ()](#apidoc.element.grunt.util._.prototype.pullAllBy)
- description and source-code
```javascript
pullAllBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.pullAt"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>pullAt ()](#apidoc.element.grunt.util._.prototype.pullAt)
- description and source-code
```javascript
pullAt = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.push"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>push ()](#apidoc.element.grunt.util._.prototype.push)
- description and source-code
```javascript
push = function () {
  var args = arguments;
  if (retUnwrapped && !this.__chain__) {
    return func.apply(this.value(), args);
  }
  return this[chainName](function(value) {
    return func.apply(value, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.q"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>q ()](#apidoc.element.grunt.util._.prototype.q)
- description and source-code
```javascript
q = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.quote"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>quote ()](#apidoc.element.grunt.util._.prototype.quote)
- description and source-code
```javascript
quote = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.random"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>random ()](#apidoc.element.grunt.util._.prototype.random)
- description and source-code
```javascript
random = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.range"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>range ()](#apidoc.element.grunt.util._.prototype.range)
- description and source-code
```javascript
range = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.rangeRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rangeRight ()](#apidoc.element.grunt.util._.prototype.rangeRight)
- description and source-code
```javascript
rangeRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.rearg"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rearg ()](#apidoc.element.grunt.util._.prototype.rearg)
- description and source-code
```javascript
rearg = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.reduce"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>reduce ()](#apidoc.element.grunt.util._.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.reduceRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>reduceRight ()](#apidoc.element.grunt.util._.prototype.reduceRight)
- description and source-code
```javascript
reduceRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.reject"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>reject ()](#apidoc.element.grunt.util._.prototype.reject)
- description and source-code
```javascript
reject = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.remove"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>remove ()](#apidoc.element.grunt.util._.prototype.remove)
- description and source-code
```javascript
remove = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.repeat"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>repeat ()](#apidoc.element.grunt.util._.prototype.repeat)
- description and source-code
```javascript
repeat = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.replace"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>replace ()](#apidoc.element.grunt.util._.prototype.replace)
- description and source-code
```javascript
replace = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.replaceAll"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>replaceAll ()](#apidoc.element.grunt.util._.prototype.replaceAll)
- description and source-code
```javascript
replaceAll = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.rest"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rest ()](#apidoc.element.grunt.util._.prototype.rest)
- description and source-code
```javascript
rest = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.result"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>result ()](#apidoc.element.grunt.util._.prototype.result)
- description and source-code
```javascript
result = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.reverse"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>reverse ()](#apidoc.element.grunt.util._.prototype.reverse)
- description and source-code
```javascript
function wrapperReverse() {
  var value = this.__wrapped__;
  if (value instanceof LazyWrapper) {
    var wrapped = value;
    if (this.__actions__.length) {
      wrapped = new LazyWrapper(this);
    }
    wrapped = wrapped.reverse();
    wrapped.__actions__.push({ 'func': thru, 'args': [reverse], 'thisArg': undefined });
    return new LodashWrapper(wrapped, this.__chain__);
  }
  return this.thru(reverse);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.rjust"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rjust ()](#apidoc.element.grunt.util._.prototype.rjust)
- description and source-code
```javascript
rjust = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.round"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>round ()](#apidoc.element.grunt.util._.prototype.round)
- description and source-code
```javascript
round = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.rpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rpad ()](#apidoc.element.grunt.util._.prototype.rpad)
- description and source-code
```javascript
rpad = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.rstrip"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rstrip ()](#apidoc.element.grunt.util._.prototype.rstrip)
- description and source-code
```javascript
rstrip = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.rtrim"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>rtrim ()](#apidoc.element.grunt.util._.prototype.rtrim)
- description and source-code
```javascript
rtrim = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.runInContext"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>runInContext ()](#apidoc.element.grunt.util._.prototype.runInContext)
- description and source-code
```javascript
runInContext = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sample"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sample ()](#apidoc.element.grunt.util._.prototype.sample)
- description and source-code
```javascript
sample = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sampleSize"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sampleSize ()](#apidoc.element.grunt.util._.prototype.sampleSize)
- description and source-code
```javascript
sampleSize = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.set"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>set ()](#apidoc.element.grunt.util._.prototype.set)
- description and source-code
```javascript
set = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.setWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>setWith ()](#apidoc.element.grunt.util._.prototype.setWith)
- description and source-code
```javascript
setWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.shift"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>shift ()](#apidoc.element.grunt.util._.prototype.shift)
- description and source-code
```javascript
shift = function () {
  var args = arguments;
  if (retUnwrapped && !this.__chain__) {
    return func.apply(this.value(), args);
  }
  return this[chainName](function(value) {
    return func.apply(value, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.shuffle"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>shuffle ()](#apidoc.element.grunt.util._.prototype.shuffle)
- description and source-code
```javascript
shuffle = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.size"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>size ()](#apidoc.element.grunt.util._.prototype.size)
- description and source-code
```javascript
size = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.slice"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>slice ()](#apidoc.element.grunt.util._.prototype.slice)
- description and source-code
```javascript
slice = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.slugify"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>slugify ()](#apidoc.element.grunt.util._.prototype.slugify)
- description and source-code
```javascript
slugify = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.snakeCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>snakeCase ()](#apidoc.element.grunt.util._.prototype.snakeCase)
- description and source-code
```javascript
snakeCase = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.some"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>some ()](#apidoc.element.grunt.util._.prototype.some)
- description and source-code
```javascript
some = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sort"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sort ()](#apidoc.element.grunt.util._.prototype.sort)
- description and source-code
```javascript
sort = function () {
  var args = arguments;
  if (retUnwrapped && !this.__chain__) {
    return func.apply(this.value(), args);
  }
  return this[chainName](function(value) {
    return func.apply(value, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortBy ()](#apidoc.element.grunt.util._.prototype.sortBy)
- description and source-code
```javascript
sortBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortedIndex"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedIndex ()](#apidoc.element.grunt.util._.prototype.sortedIndex)
- description and source-code
```javascript
sortedIndex = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortedIndexBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedIndexBy ()](#apidoc.element.grunt.util._.prototype.sortedIndexBy)
- description and source-code
```javascript
sortedIndexBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortedIndexOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedIndexOf ()](#apidoc.element.grunt.util._.prototype.sortedIndexOf)
- description and source-code
```javascript
sortedIndexOf = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortedLastIndex"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedLastIndex ()](#apidoc.element.grunt.util._.prototype.sortedLastIndex)
- description and source-code
```javascript
sortedLastIndex = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortedLastIndexBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedLastIndexBy ()](#apidoc.element.grunt.util._.prototype.sortedLastIndexBy)
- description and source-code
```javascript
sortedLastIndexBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortedLastIndexOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedLastIndexOf ()](#apidoc.element.grunt.util._.prototype.sortedLastIndexOf)
- description and source-code
```javascript
sortedLastIndexOf = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortedUniq"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedUniq ()](#apidoc.element.grunt.util._.prototype.sortedUniq)
- description and source-code
```javascript
sortedUniq = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sortedUniqBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sortedUniqBy ()](#apidoc.element.grunt.util._.prototype.sortedUniqBy)
- description and source-code
```javascript
sortedUniqBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.splice"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>splice ()](#apidoc.element.grunt.util._.prototype.splice)
- description and source-code
```javascript
splice = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.split"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>split ()](#apidoc.element.grunt.util._.prototype.split)
- description and source-code
```javascript
split = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.spread"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>spread ()](#apidoc.element.grunt.util._.prototype.spread)
- description and source-code
```javascript
spread = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sprintf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sprintf ()](#apidoc.element.grunt.util._.prototype.sprintf)
- description and source-code
```javascript
sprintf = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.startCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>startCase ()](#apidoc.element.grunt.util._.prototype.startCase)
- description and source-code
```javascript
startCase = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.startsWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>startsWith ()](#apidoc.element.grunt.util._.prototype.startsWith)
- description and source-code
```javascript
startsWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.strLeft"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strLeft ()](#apidoc.element.grunt.util._.prototype.strLeft)
- description and source-code
```javascript
strLeft = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.strLeftBack"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strLeftBack ()](#apidoc.element.grunt.util._.prototype.strLeftBack)
- description and source-code
```javascript
strLeftBack = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.strRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strRight ()](#apidoc.element.grunt.util._.prototype.strRight)
- description and source-code
```javascript
strRight = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.strRightBack"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strRightBack ()](#apidoc.element.grunt.util._.prototype.strRightBack)
- description and source-code
```javascript
strRightBack = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.strip"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>strip ()](#apidoc.element.grunt.util._.prototype.strip)
- description and source-code
```javascript
strip = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.stripTags"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>stripTags ()](#apidoc.element.grunt.util._.prototype.stripTags)
- description and source-code
```javascript
stripTags = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.subtract"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>subtract ()](#apidoc.element.grunt.util._.prototype.subtract)
- description and source-code
```javascript
subtract = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.succ"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>succ ()](#apidoc.element.grunt.util._.prototype.succ)
- description and source-code
```javascript
succ = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sum"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sum ()](#apidoc.element.grunt.util._.prototype.sum)
- description and source-code
```javascript
sum = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.sumBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>sumBy ()](#apidoc.element.grunt.util._.prototype.sumBy)
- description and source-code
```javascript
sumBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.surround"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>surround ()](#apidoc.element.grunt.util._.prototype.surround)
- description and source-code
```javascript
surround = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.swapCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>swapCase ()](#apidoc.element.grunt.util._.prototype.swapCase)
- description and source-code
```javascript
swapCase = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.tail"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>tail ()](#apidoc.element.grunt.util._.prototype.tail)
- description and source-code
```javascript
tail = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.take"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>take ()](#apidoc.element.grunt.util._.prototype.take)
- description and source-code
```javascript
take = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.takeRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>takeRight ()](#apidoc.element.grunt.util._.prototype.takeRight)
- description and source-code
```javascript
takeRight = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.takeRightWhile"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>takeRightWhile ()](#apidoc.element.grunt.util._.prototype.takeRightWhile)
- description and source-code
```javascript
takeRightWhile = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.takeWhile"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>takeWhile ()](#apidoc.element.grunt.util._.prototype.takeWhile)
- description and source-code
```javascript
takeWhile = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.tap"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>tap ()](#apidoc.element.grunt.util._.prototype.tap)
- description and source-code
```javascript
tap = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.template"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>template ()](#apidoc.element.grunt.util._.prototype.template)
- description and source-code
```javascript
template = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.throttle"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>throttle ()](#apidoc.element.grunt.util._.prototype.throttle)
- description and source-code
```javascript
throttle = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.thru"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>thru ()](#apidoc.element.grunt.util._.prototype.thru)
- description and source-code
```javascript
thru = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.times"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>times ()](#apidoc.element.grunt.util._.prototype.times)
- description and source-code
```javascript
times = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.titleize"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>titleize ()](#apidoc.element.grunt.util._.prototype.titleize)
- description and source-code
```javascript
titleize = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toArray"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toArray ()](#apidoc.element.grunt.util._.prototype.toArray)
- description and source-code
```javascript
toArray = function () {
  var value = this.__wrapped__,
      args = isTaker ? [1] : arguments,
      isLazy = value instanceof LazyWrapper,
      iteratee = args[0],
      useLazy = isLazy || isArray(value);

  var interceptor = function(value) {
    var result = lodashFunc.apply(lodash, arrayPush([value], args));
    return (isTaker && chainAll) ? result[0] : result;
  };

  if (useLazy && checkIteratee && typeof iteratee == 'function' && iteratee.length != 1) {
    // Avoid lazy use if the iteratee has a "length" value other than '1'.
    isLazy = useLazy = false;
  }
  var chainAll = this.__chain__,
      isHybrid = !!this.__actions__.length,
      isUnwrapped = retUnwrapped && !chainAll,
      onlyLazy = isLazy && !isHybrid;

  if (!retUnwrapped && useLazy) {
    value = onlyLazy ? value : new LazyWrapper(this);
    var result = func.apply(value, args);
    result.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(result, chainAll);
  }
  if (isUnwrapped && onlyLazy) {
    return func.apply(this, args);
  }
  result = this.thru(interceptor);
  return isUnwrapped ? (isTaker ? result.value()[0] : result.value()) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toBool"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toBool ()](#apidoc.element.grunt.util._.prototype.toBool)
- description and source-code
```javascript
toBool = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toBoolean"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toBoolean ()](#apidoc.element.grunt.util._.prototype.toBoolean)
- description and source-code
```javascript
toBoolean = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toInteger"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toInteger ()](#apidoc.element.grunt.util._.prototype.toInteger)
- description and source-code
```javascript
toInteger = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toJSON ()](#apidoc.element.grunt.util._.prototype.toJSON)
- description and source-code
```javascript
function wrapperValue() {
  return baseWrapperValue(this.__wrapped__, this.__actions__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toLength"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toLength ()](#apidoc.element.grunt.util._.prototype.toLength)
- description and source-code
```javascript
toLength = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toLower"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toLower ()](#apidoc.element.grunt.util._.prototype.toLower)
- description and source-code
```javascript
toLower = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toNumber"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toNumber ()](#apidoc.element.grunt.util._.prototype.toNumber)
- description and source-code
```javascript
toNumber = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toPairs"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toPairs ()](#apidoc.element.grunt.util._.prototype.toPairs)
- description and source-code
```javascript
toPairs = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toPairsIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toPairsIn ()](#apidoc.element.grunt.util._.prototype.toPairsIn)
- description and source-code
```javascript
toPairsIn = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toPath"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toPath ()](#apidoc.element.grunt.util._.prototype.toPath)
- description and source-code
```javascript
toPath = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toPlainObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toPlainObject ()](#apidoc.element.grunt.util._.prototype.toPlainObject)
- description and source-code
```javascript
toPlainObject = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toSafeInteger"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toSafeInteger ()](#apidoc.element.grunt.util._.prototype.toSafeInteger)
- description and source-code
```javascript
toSafeInteger = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toSentence"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toSentence ()](#apidoc.element.grunt.util._.prototype.toSentence)
- description and source-code
```javascript
toSentence = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toSentenceSerial"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toSentenceSerial ()](#apidoc.element.grunt.util._.prototype.toSentenceSerial)
- description and source-code
```javascript
toSentenceSerial = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toString"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toString ()](#apidoc.element.grunt.util._.prototype.toString)
- description and source-code
```javascript
toString = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.toUpper"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>toUpper ()](#apidoc.element.grunt.util._.prototype.toUpper)
- description and source-code
```javascript
toUpper = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.transform"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>transform ()](#apidoc.element.grunt.util._.prototype.transform)
- description and source-code
```javascript
transform = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.trim"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>trim ()](#apidoc.element.grunt.util._.prototype.trim)
- description and source-code
```javascript
trim = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.trimEnd"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>trimEnd ()](#apidoc.element.grunt.util._.prototype.trimEnd)
- description and source-code
```javascript
trimEnd = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.trimStart"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>trimStart ()](#apidoc.element.grunt.util._.prototype.trimStart)
- description and source-code
```javascript
trimStart = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.truncate"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>truncate ()](#apidoc.element.grunt.util._.prototype.truncate)
- description and source-code
```javascript
truncate = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unary"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unary ()](#apidoc.element.grunt.util._.prototype.unary)
- description and source-code
```javascript
unary = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.underscored"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>underscored ()](#apidoc.element.grunt.util._.prototype.underscored)
- description and source-code
```javascript
underscored = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unescape"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unescape ()](#apidoc.element.grunt.util._.prototype.unescape)
- description and source-code
```javascript
unescape = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unescapeHTML"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unescapeHTML ()](#apidoc.element.grunt.util._.prototype.unescapeHTML)
- description and source-code
```javascript
unescapeHTML = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.union"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>union ()](#apidoc.element.grunt.util._.prototype.union)
- description and source-code
```javascript
union = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unionBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unionBy ()](#apidoc.element.grunt.util._.prototype.unionBy)
- description and source-code
```javascript
unionBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unionWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unionWith ()](#apidoc.element.grunt.util._.prototype.unionWith)
- description and source-code
```javascript
unionWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.uniq"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>uniq ()](#apidoc.element.grunt.util._.prototype.uniq)
- description and source-code
```javascript
uniq = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.uniqBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>uniqBy ()](#apidoc.element.grunt.util._.prototype.uniqBy)
- description and source-code
```javascript
uniqBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.uniqWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>uniqWith ()](#apidoc.element.grunt.util._.prototype.uniqWith)
- description and source-code
```javascript
uniqWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.uniqueId"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>uniqueId ()](#apidoc.element.grunt.util._.prototype.uniqueId)
- description and source-code
```javascript
uniqueId = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unquote"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unquote ()](#apidoc.element.grunt.util._.prototype.unquote)
- description and source-code
```javascript
unquote = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unset"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unset ()](#apidoc.element.grunt.util._.prototype.unset)
- description and source-code
```javascript
unset = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unshift"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unshift ()](#apidoc.element.grunt.util._.prototype.unshift)
- description and source-code
```javascript
unshift = function () {
  var args = arguments;
  if (retUnwrapped && !this.__chain__) {
    return func.apply(this.value(), args);
  }
  return this[chainName](function(value) {
    return func.apply(value, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unzip"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unzip ()](#apidoc.element.grunt.util._.prototype.unzip)
- description and source-code
```javascript
unzip = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.unzipWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>unzipWith ()](#apidoc.element.grunt.util._.prototype.unzipWith)
- description and source-code
```javascript
unzipWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.upperCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>upperCase ()](#apidoc.element.grunt.util._.prototype.upperCase)
- description and source-code
```javascript
upperCase = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.upperFirst"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>upperFirst ()](#apidoc.element.grunt.util._.prototype.upperFirst)
- description and source-code
```javascript
upperFirst = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.value"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>value ()](#apidoc.element.grunt.util._.prototype.value)
- description and source-code
```javascript
function wrapperValue() {
  return baseWrapperValue(this.__wrapped__, this.__actions__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.valueOf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>valueOf ()](#apidoc.element.grunt.util._.prototype.valueOf)
- description and source-code
```javascript
function wrapperValue() {
  return baseWrapperValue(this.__wrapped__, this.__actions__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.values"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>values ()](#apidoc.element.grunt.util._.prototype.values)
- description and source-code
```javascript
values = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.valuesIn"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>valuesIn ()](#apidoc.element.grunt.util._.prototype.valuesIn)
- description and source-code
```javascript
valuesIn = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.vsprintf"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>vsprintf ()](#apidoc.element.grunt.util._.prototype.vsprintf)
- description and source-code
```javascript
vsprintf = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.without"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>without ()](#apidoc.element.grunt.util._.prototype.without)
- description and source-code
```javascript
without = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.words"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>words ()](#apidoc.element.grunt.util._.prototype.words)
- description and source-code
```javascript
words = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.wrap"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>wrap ()](#apidoc.element.grunt.util._.prototype.wrap)
- description and source-code
```javascript
wrap = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.xor"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>xor ()](#apidoc.element.grunt.util._.prototype.xor)
- description and source-code
```javascript
xor = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.xorBy"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>xorBy ()](#apidoc.element.grunt.util._.prototype.xorBy)
- description and source-code
```javascript
xorBy = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.xorWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>xorWith ()](#apidoc.element.grunt.util._.prototype.xorWith)
- description and source-code
```javascript
xorWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.zip"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>zip ()](#apidoc.element.grunt.util._.prototype.zip)
- description and source-code
```javascript
zip = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.zipObject"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>zipObject ()](#apidoc.element.grunt.util._.prototype.zipObject)
- description and source-code
```javascript
zipObject = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.zipObjectDeep"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>zipObjectDeep ()](#apidoc.element.grunt.util._.prototype.zipObjectDeep)
- description and source-code
```javascript
zipObjectDeep = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.prototype.zipWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.prototype.</span>zipWith ()](#apidoc.element.grunt.util._.prototype.zipWith)
- description and source-code
```javascript
zipWith = function () {
  var chainAll = this.__chain__;
  if (chain || chainAll) {
    var result = object(this.__wrapped__),
        actions = result.__actions__ = copyArray(this.__actions__);

    actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
    result.__chain__ = chainAll;
    return result;
  }
  return func.apply(object, arrayPush([this.value()], arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util._.str.prototype"></a>[module grunt.util._.str.prototype](#apidoc.module.grunt.util._.str.prototype)

#### <a name="apidoc.element.grunt.util._.str.prototype.camelcase"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>camelcase ()](#apidoc.element.grunt.util._.str.prototype.camelcase)
- description and source-code
```javascript
camelcase = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.camelize"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>camelize ()](#apidoc.element.grunt.util._.str.prototype.camelize)
- description and source-code
```javascript
camelize = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.capitalize"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>capitalize ()](#apidoc.element.grunt.util._.str.prototype.capitalize)
- description and source-code
```javascript
capitalize = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.center"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>center ()](#apidoc.element.grunt.util._.str.prototype.center)
- description and source-code
```javascript
center = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.chars"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>chars ()](#apidoc.element.grunt.util._.str.prototype.chars)
- description and source-code
```javascript
chars = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.chop"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>chop ()](#apidoc.element.grunt.util._.str.prototype.chop)
- description and source-code
```javascript
chop = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.classify"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>classify ()](#apidoc.element.grunt.util._.str.prototype.classify)
- description and source-code
```javascript
classify = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.clean"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>clean ()](#apidoc.element.grunt.util._.str.prototype.clean)
- description and source-code
```javascript
clean = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.cleanDiacritics"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>cleanDiacritics ()](#apidoc.element.grunt.util._.str.prototype.cleanDiacritics)
- description and source-code
```javascript
cleanDiacritics = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.concat"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>concat ()](#apidoc.element.grunt.util._.str.prototype.concat)
- description and source-code
```javascript
concat = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.contains"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>contains ()](#apidoc.element.grunt.util._.str.prototype.contains)
- description and source-code
```javascript
contains = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.count"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>count ()](#apidoc.element.grunt.util._.str.prototype.count)
- description and source-code
```javascript
count = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.dasherize"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>dasherize ()](#apidoc.element.grunt.util._.str.prototype.dasherize)
- description and source-code
```javascript
dasherize = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.decapitalize"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>decapitalize ()](#apidoc.element.grunt.util._.str.prototype.decapitalize)
- description and source-code
```javascript
decapitalize = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.dedent"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>dedent ()](#apidoc.element.grunt.util._.str.prototype.dedent)
- description and source-code
```javascript
dedent = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.endsWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>endsWith ()](#apidoc.element.grunt.util._.str.prototype.endsWith)
- description and source-code
```javascript
endsWith = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.escapeHTML"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>escapeHTML ()](#apidoc.element.grunt.util._.str.prototype.escapeHTML)
- description and source-code
```javascript
escapeHTML = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.escapeRegExp"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>escapeRegExp ()](#apidoc.element.grunt.util._.str.prototype.escapeRegExp)
- description and source-code
```javascript
escapeRegExp = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.exports"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>exports ()](#apidoc.element.grunt.util._.str.prototype.exports)
- description and source-code
```javascript
exports = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.humanize"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>humanize ()](#apidoc.element.grunt.util._.str.prototype.humanize)
- description and source-code
```javascript
humanize = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.include"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>include ()](#apidoc.element.grunt.util._.str.prototype.include)
- description and source-code
```javascript
include = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.insert"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>insert ()](#apidoc.element.grunt.util._.str.prototype.insert)
- description and source-code
```javascript
insert = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.isBlank"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>isBlank ()](#apidoc.element.grunt.util._.str.prototype.isBlank)
- description and source-code
```javascript
isBlank = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.join"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>join ()](#apidoc.element.grunt.util._.str.prototype.join)
- description and source-code
```javascript
join = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.levenshtein"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>levenshtein ()](#apidoc.element.grunt.util._.str.prototype.levenshtein)
- description and source-code
```javascript
levenshtein = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.lines"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>lines ()](#apidoc.element.grunt.util._.str.prototype.lines)
- description and source-code
```javascript
lines = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.ljust"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>ljust ()](#apidoc.element.grunt.util._.str.prototype.ljust)
- description and source-code
```javascript
ljust = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.lpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>lpad ()](#apidoc.element.grunt.util._.str.prototype.lpad)
- description and source-code
```javascript
lpad = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.lrpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>lrpad ()](#apidoc.element.grunt.util._.str.prototype.lrpad)
- description and source-code
```javascript
lrpad = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.lstrip"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>lstrip ()](#apidoc.element.grunt.util._.str.prototype.lstrip)
- description and source-code
```javascript
lstrip = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.ltrim"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>ltrim ()](#apidoc.element.grunt.util._.str.prototype.ltrim)
- description and source-code
```javascript
ltrim = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.map"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>map ()](#apidoc.element.grunt.util._.str.prototype.map)
- description and source-code
```javascript
map = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.mapChars"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>mapChars ()](#apidoc.element.grunt.util._.str.prototype.mapChars)
- description and source-code
```javascript
mapChars = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.naturalCmp"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>naturalCmp ()](#apidoc.element.grunt.util._.str.prototype.naturalCmp)
- description and source-code
```javascript
naturalCmp = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.numberFormat"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>numberFormat ()](#apidoc.element.grunt.util._.str.prototype.numberFormat)
- description and source-code
```javascript
numberFormat = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.pad"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>pad ()](#apidoc.element.grunt.util._.str.prototype.pad)
- description and source-code
```javascript
pad = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.pred"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>pred ()](#apidoc.element.grunt.util._.str.prototype.pred)
- description and source-code
```javascript
pred = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.prune"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>prune ()](#apidoc.element.grunt.util._.str.prototype.prune)
- description and source-code
```javascript
prune = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.q"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>q ()](#apidoc.element.grunt.util._.str.prototype.q)
- description and source-code
```javascript
q = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.quote"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>quote ()](#apidoc.element.grunt.util._.str.prototype.quote)
- description and source-code
```javascript
quote = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.repeat"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>repeat ()](#apidoc.element.grunt.util._.str.prototype.repeat)
- description and source-code
```javascript
repeat = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.replace"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>replace ()](#apidoc.element.grunt.util._.str.prototype.replace)
- description and source-code
```javascript
replace = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.replaceAll"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>replaceAll ()](#apidoc.element.grunt.util._.str.prototype.replaceAll)
- description and source-code
```javascript
replaceAll = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.reverse"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>reverse ()](#apidoc.element.grunt.util._.str.prototype.reverse)
- description and source-code
```javascript
reverse = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.rjust"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>rjust ()](#apidoc.element.grunt.util._.str.prototype.rjust)
- description and source-code
```javascript
rjust = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.rpad"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>rpad ()](#apidoc.element.grunt.util._.str.prototype.rpad)
- description and source-code
```javascript
rpad = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.rstrip"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>rstrip ()](#apidoc.element.grunt.util._.str.prototype.rstrip)
- description and source-code
```javascript
rstrip = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.rtrim"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>rtrim ()](#apidoc.element.grunt.util._.str.prototype.rtrim)
- description and source-code
```javascript
rtrim = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.slice"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>slice ()](#apidoc.element.grunt.util._.str.prototype.slice)
- description and source-code
```javascript
slice = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.slugify"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>slugify ()](#apidoc.element.grunt.util._.str.prototype.slugify)
- description and source-code
```javascript
slugify = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.splice"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>splice ()](#apidoc.element.grunt.util._.str.prototype.splice)
- description and source-code
```javascript
splice = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.split"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>split ()](#apidoc.element.grunt.util._.str.prototype.split)
- description and source-code
```javascript
split = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.sprintf"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>sprintf ()](#apidoc.element.grunt.util._.str.prototype.sprintf)
- description and source-code
```javascript
sprintf = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.startsWith"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>startsWith ()](#apidoc.element.grunt.util._.str.prototype.startsWith)
- description and source-code
```javascript
startsWith = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.strLeft"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strLeft ()](#apidoc.element.grunt.util._.str.prototype.strLeft)
- description and source-code
```javascript
strLeft = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.strLeftBack"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strLeftBack ()](#apidoc.element.grunt.util._.str.prototype.strLeftBack)
- description and source-code
```javascript
strLeftBack = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.strRight"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strRight ()](#apidoc.element.grunt.util._.str.prototype.strRight)
- description and source-code
```javascript
strRight = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.strRightBack"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strRightBack ()](#apidoc.element.grunt.util._.str.prototype.strRightBack)
- description and source-code
```javascript
strRightBack = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.strip"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>strip ()](#apidoc.element.grunt.util._.str.prototype.strip)
- description and source-code
```javascript
strip = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.stripTags"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>stripTags ()](#apidoc.element.grunt.util._.str.prototype.stripTags)
- description and source-code
```javascript
stripTags = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.substr"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>substr ()](#apidoc.element.grunt.util._.str.prototype.substr)
- description and source-code
```javascript
substr = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.substring"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>substring ()](#apidoc.element.grunt.util._.str.prototype.substring)
- description and source-code
```javascript
substring = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.succ"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>succ ()](#apidoc.element.grunt.util._.str.prototype.succ)
- description and source-code
```javascript
succ = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.surround"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>surround ()](#apidoc.element.grunt.util._.str.prototype.surround)
- description and source-code
```javascript
surround = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.swapCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>swapCase ()](#apidoc.element.grunt.util._.str.prototype.swapCase)
- description and source-code
```javascript
swapCase = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.tap"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>tap ()](#apidoc.element.grunt.util._.str.prototype.tap)
- description and source-code
```javascript
tap = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.titleize"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>titleize ()](#apidoc.element.grunt.util._.str.prototype.titleize)
- description and source-code
```javascript
titleize = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.toBool"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toBool ()](#apidoc.element.grunt.util._.str.prototype.toBool)
- description and source-code
```javascript
toBool = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.toBoolean"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toBoolean ()](#apidoc.element.grunt.util._.str.prototype.toBoolean)
- description and source-code
```javascript
toBoolean = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.toLowerCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toLowerCase ()](#apidoc.element.grunt.util._.str.prototype.toLowerCase)
- description and source-code
```javascript
toLowerCase = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.toNumber"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toNumber ()](#apidoc.element.grunt.util._.str.prototype.toNumber)
- description and source-code
```javascript
toNumber = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.toSentence"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toSentence ()](#apidoc.element.grunt.util._.str.prototype.toSentence)
- description and source-code
```javascript
toSentence = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.toSentenceSerial"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toSentenceSerial ()](#apidoc.element.grunt.util._.str.prototype.toSentenceSerial)
- description and source-code
```javascript
toSentenceSerial = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.toUpperCase"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>toUpperCase ()](#apidoc.element.grunt.util._.str.prototype.toUpperCase)
- description and source-code
```javascript
toUpperCase = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.trim"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>trim ()](#apidoc.element.grunt.util._.str.prototype.trim)
- description and source-code
```javascript
trim = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.truncate"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>truncate ()](#apidoc.element.grunt.util._.str.prototype.truncate)
- description and source-code
```javascript
truncate = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.underscored"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>underscored ()](#apidoc.element.grunt.util._.str.prototype.underscored)
- description and source-code
```javascript
underscored = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.unescapeHTML"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>unescapeHTML ()](#apidoc.element.grunt.util._.str.prototype.unescapeHTML)
- description and source-code
```javascript
unescapeHTML = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.unquote"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>unquote ()](#apidoc.element.grunt.util._.str.prototype.unquote)
- description and source-code
```javascript
unquote = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.value"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>value ()](#apidoc.element.grunt.util._.str.prototype.value)
- description and source-code
```javascript
function value() {
  return this._wrapped;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.vsprintf"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>vsprintf ()](#apidoc.element.grunt.util._.str.prototype.vsprintf)
- description and source-code
```javascript
vsprintf = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.words"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>words ()](#apidoc.element.grunt.util._.str.prototype.words)
- description and source-code
```javascript
words = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util._.str.prototype.wrap"></a>[function <span class="apidocSignatureSpan">grunt.util._.str.prototype.</span>wrap ()](#apidoc.element.grunt.util._.str.prototype.wrap)
- description and source-code
```javascript
wrap = function () {
  var args = [this._wrapped].concat(Array.prototype.slice.call(arguments));
  var res = fn.apply(null, args);
  // if the result is non-string stop the chain and return the value
  return typeof res === 'string' ? new s(res) : res;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util.async"></a>[module grunt.util.async](#apidoc.module.grunt.util.async)

#### <a name="apidoc.element.grunt.util.async.all"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>all (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.all)
- description and source-code
```javascript
all = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.any"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>any (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.any)
- description and source-code
```javascript
any = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.apply"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>apply ()](#apidoc.element.grunt.util.async.apply)
- description and source-code
```javascript
apply = function () {
    var length = Math.max(arguments.length - startIndex, 0);
    var rest = Array(length);
    for (var index = 0; index < length; index++) {
        rest[index] = arguments[index + startIndex];
    }
    switch (startIndex) {
        case 0: return func.call(this, rest);
        case 1: return func.call(this, arguments[0], rest);
    }
    // Currently unused but handle cases outside of the switch statement:
    // var args = Array(startIndex + 1);
    // for (index = 0; index < startIndex; index++) {
    //     args[index] = arguments[index];
    // }
    // args[startIndex] = rest;
    // return func.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.applyEach"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>applyEach ()](#apidoc.element.grunt.util.async.applyEach)
- description and source-code
```javascript
applyEach = function () {
    var length = Math.max(arguments.length - startIndex, 0);
    var rest = Array(length);
    for (var index = 0; index < length; index++) {
        rest[index] = arguments[index + startIndex];
    }
    switch (startIndex) {
        case 0: return func.call(this, rest);
        case 1: return func.call(this, arguments[0], rest);
    }
    // Currently unused but handle cases outside of the switch statement:
    // var args = Array(startIndex + 1);
    // for (index = 0; index < startIndex; index++) {
    //     args[index] = arguments[index];
    // }
    // args[startIndex] = rest;
    // return func.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.applyEachSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>applyEachSeries ()](#apidoc.element.grunt.util.async.applyEachSeries)
- description and source-code
```javascript
applyEachSeries = function () {
    var length = Math.max(arguments.length - startIndex, 0);
    var rest = Array(length);
    for (var index = 0; index < length; index++) {
        rest[index] = arguments[index + startIndex];
    }
    switch (startIndex) {
        case 0: return func.call(this, rest);
        case 1: return func.call(this, arguments[0], rest);
    }
    // Currently unused but handle cases outside of the switch statement:
    // var args = Array(startIndex + 1);
    // for (index = 0; index < startIndex; index++) {
    //     args[index] = arguments[index];
    // }
    // args[startIndex] = rest;
    // return func.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.asyncify"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>asyncify (func)](#apidoc.element.grunt.util.async.asyncify)
- description and source-code
```javascript
function asyncify(func) {
    return _restParam(function (args) {
        var callback = args.pop();
        var result;
        try {
            result = func.apply(this, args);
        } catch (e) {
            return callback(e);
        }
        // if result is Promise object
        if (_isObject(result) && typeof result.then === "function") {
            result.then(function(value) {
                callback(null, value);
            })["catch"](function(err) {
                callback(err.message ? err : new Error(err));
            });
        } else {
            callback(null, result);
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.auto"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>auto (tasks, concurrency, callback)](#apidoc.element.grunt.util.async.auto)
- description and source-code
```javascript
auto = function (tasks, concurrency, callback) {
    if (typeof arguments[1] === 'function') {
        // concurrency is optional, shift the args.
        callback = concurrency;
        concurrency = null;
    }
    callback = _once(callback || noop);
    var keys = _keys(tasks);
    var remainingTasks = keys.length;
    if (!remainingTasks) {
        return callback(null);
    }
    if (!concurrency) {
        concurrency = remainingTasks;
    }

    var results = {};
    var runningTasks = 0;

    var hasError = false;

    var listeners = [];
    function addListener(fn) {
        listeners.unshift(fn);
    }
    function removeListener(fn) {
        var idx = _indexOf(listeners, fn);
        if (idx >= 0) listeners.splice(idx, 1);
    }
    function taskComplete() {
        remainingTasks--;
        _arrayEach(listeners.slice(0), function (fn) {
            fn();
        });
    }

    addListener(function () {
        if (!remainingTasks) {
            callback(null, results);
        }
    });

    _arrayEach(keys, function (k) {
        if (hasError) return;
        var task = _isArray(tasks[k]) ? tasks[k]: [tasks[k]];
        var taskCallback = _restParam(function(err, args) {
            runningTasks--;
            if (args.length <= 1) {
                args = args[0];
            }
            if (err) {
                var safeResults = {};
                _forEachOf(results, function(val, rkey) {
                    safeResults[rkey] = val;
                });
                safeResults[k] = args;
                hasError = true;

                callback(err, safeResults);
            }
            else {
                results[k] = args;
                async.setImmediate(taskComplete);
            }
        });
        var requires = task.slice(0, task.length - 1);
        // prevent dead-locks
        var len = requires.length;
        var dep;
        while (len--) {
            if (!(dep = tasks[requires[len]])) {
                throw new Error('Has nonexistent dependency in ' + requires.join(', '));
            }
            if (_isArray(dep) && _indexOf(dep, k) >= 0) {
                throw new Error('Has cyclic dependencies');
            }
        }
        function ready() {
            return runningTasks < concurrency && _reduce(requires, function (a, x) {
                return (a && results.hasOwnProperty(x));
            }, true) && !results.hasOwnProperty(k);
        }
        if (ready()) {
            runningTasks++;
            task[task.length - 1](taskCallback, results);
        }
        else {
            addListener(listener);
        }
        function listener() {
            if (ready()) {
                runningTasks++;
                removeListener(listener);
                task[task.length - 1](taskCallback, results);
            }
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.cargo"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>cargo (worker, payload)](#apidoc.element.grunt.util.async.cargo)
- description and source-code
```javascript
cargo = function (worker, payload) {
    return _queue(worker, 1, payload);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.compose"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>compose ()](#apidoc.element.grunt.util.async.compose)
- description and source-code
```javascript
compose = function () {
    return async.seq.apply(null, Array.prototype.reverse.call(arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.concat"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>concat (obj, iterator, callback)](#apidoc.element.grunt.util.async.concat)
- description and source-code
```javascript
concat = function (obj, iterator, callback) {
    return fn(async.eachOf, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.concatSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>concatSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.concatSeries)
- description and source-code
```javascript
concatSeries = function (obj, iterator, callback) {
    return fn(async.eachOfSeries, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.constant"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>constant ()](#apidoc.element.grunt.util.async.constant)
- description and source-code
```javascript
constant = function () {
    var length = Math.max(arguments.length - startIndex, 0);
    var rest = Array(length);
    for (var index = 0; index < length; index++) {
        rest[index] = arguments[index + startIndex];
    }
    switch (startIndex) {
        case 0: return func.call(this, rest);
        case 1: return func.call(this, arguments[0], rest);
    }
    // Currently unused but handle cases outside of the switch statement:
    // var args = Array(startIndex + 1);
    // for (index = 0; index < startIndex; index++) {
    //     args[index] = arguments[index];
    // }
    // args[startIndex] = rest;
    // return func.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.detect"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>detect (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.detect)
- description and source-code
```javascript
detect = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.detectLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>detectLimit (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.detectLimit)
- description and source-code
```javascript
detectLimit = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.detectSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>detectSeries (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.detectSeries)
- description and source-code
```javascript
detectSeries = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.dir"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>dir ()](#apidoc.element.grunt.util.async.dir)
- description and source-code
```javascript
dir = function () {
    var length = Math.max(arguments.length - startIndex, 0);
    var rest = Array(length);
    for (var index = 0; index < length; index++) {
        rest[index] = arguments[index + startIndex];
    }
    switch (startIndex) {
        case 0: return func.call(this, rest);
        case 1: return func.call(this, arguments[0], rest);
    }
    // Currently unused but handle cases outside of the switch statement:
    // var args = Array(startIndex + 1);
    // for (index = 0; index < startIndex; index++) {
    //     args[index] = arguments[index];
    // }
    // args[startIndex] = rest;
    // return func.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.doDuring"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>doDuring (iterator, test, callback)](#apidoc.element.grunt.util.async.doDuring)
- description and source-code
```javascript
doDuring = function (iterator, test, callback) {
    var calls = 0;
    async.during(function(next) {
        if (calls++ < 1) {
            next(null, true);
        } else {
            test.apply(this, arguments);
        }
    }, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.doUntil"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>doUntil (iterator, test, callback)](#apidoc.element.grunt.util.async.doUntil)
- description and source-code
```javascript
doUntil = function (iterator, test, callback) {
    return async.doWhilst(iterator, function() {
        return !test.apply(this, arguments);
    }, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.doWhilst"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>doWhilst (iterator, test, callback)](#apidoc.element.grunt.util.async.doWhilst)
- description and source-code
```javascript
doWhilst = function (iterator, test, callback) {
    var calls = 0;
    return async.whilst(function() {
        return ++calls <= 1 || test.apply(this, arguments);
    }, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.during"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>during (test, iterator, callback)](#apidoc.element.grunt.util.async.during)
- description and source-code
```javascript
during = function (test, iterator, callback) {
    callback = callback || noop;

    var next = _restParam(function(err, args) {
        if (err) {
            callback(err);
        } else {
            args.push(check);
            test.apply(this, args);
        }
    });

    var check = function(err, truth) {
        if (err) {
            callback(err);
        } else if (truth) {
            iterator(next);
        } else {
            callback(null);
        }
    };

    test(check);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.each"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>each (arr, iterator, callback)](#apidoc.element.grunt.util.async.each)
- description and source-code
```javascript
each = function (arr, iterator, callback) {
    return async.eachOf(arr, _withoutIndex(iterator), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.eachLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>eachLimit (arr, limit, iterator, callback)](#apidoc.element.grunt.util.async.eachLimit)
- description and source-code
```javascript
eachLimit = function (arr, limit, iterator, callback) {
    return _eachOfLimit(limit)(arr, _withoutIndex(iterator), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.eachOf"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>eachOf (object, iterator, callback)](#apidoc.element.grunt.util.async.eachOf)
- description and source-code
```javascript
eachOf = function (object, iterator, callback) {
    callback = _once(callback || noop);
    object = object || [];

    var iter = _keyIterator(object);
    var key, completed = 0;

    while ((key = iter()) != null) {
        completed += 1;
        iterator(object[key], key, only_once(done));
    }

    if (completed === 0) callback(null);

    function done(err) {
        completed--;
        if (err) {
            callback(err);
        }
        // Check key is null in case iterator isn't exhausted
        // and done resolved synchronously.
        else if (key === null && completed <= 0) {
            callback(null);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.eachOfLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>eachOfLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.eachOfLimit)
- description and source-code
```javascript
eachOfLimit = function (obj, limit, iterator, callback) {
    _eachOfLimit(limit)(obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.eachOfSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>eachOfSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.eachOfSeries)
- description and source-code
```javascript
eachOfSeries = function (obj, iterator, callback) {
    callback = _once(callback || noop);
    obj = obj || [];
    var nextKey = _keyIterator(obj);
    var key = nextKey();
    function iterate() {
        var sync = true;
        if (key === null) {
            return callback(null);
        }
        iterator(obj[key], key, only_once(function (err) {
            if (err) {
                callback(err);
            }
            else {
                key = nextKey();
                if (key === null) {
                    return callback(null);
                } else {
                    if (sync) {
                        async.setImmediate(iterate);
                    } else {
                        iterate();
                    }
                }
            }
        }));
        sync = false;
    }
    iterate();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.eachSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>eachSeries (arr, iterator, callback)](#apidoc.element.grunt.util.async.eachSeries)
- description and source-code
```javascript
eachSeries = function (arr, iterator, callback) {
    return async.eachOfSeries(arr, _withoutIndex(iterator), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.ensureAsync"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>ensureAsync (fn)](#apidoc.element.grunt.util.async.ensureAsync)
- description and source-code
```javascript
function ensureAsync(fn) {
    return _restParam(function (args) {
        var callback = args.pop();
        args.push(function () {
            var innerArgs = arguments;
            if (sync) {
                async.setImmediate(function () {
                    callback.apply(null, innerArgs);
                });
            } else {
                callback.apply(null, innerArgs);
            }
        });
        var sync = true;
        fn.apply(this, args);
        sync = false;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.every"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>every (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.every)
- description and source-code
```javascript
every = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.everyLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>everyLimit (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.everyLimit)
- description and source-code
```javascript
everyLimit = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.filter"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>filter (obj, iterator, callback)](#apidoc.element.grunt.util.async.filter)
- description and source-code
```javascript
filter = function (obj, iterator, callback) {
    return fn(async.eachOf, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.filterLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>filterLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.filterLimit)
- description and source-code
```javascript
filterLimit = function (obj, limit, iterator, callback) {
    return fn(_eachOfLimit(limit), obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.filterSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>filterSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.filterSeries)
- description and source-code
```javascript
filterSeries = function (obj, iterator, callback) {
    return fn(async.eachOfSeries, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.foldl"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>foldl (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.foldl)
- description and source-code
```javascript
foldl = function (arr, memo, iterator, callback) {
    async.eachOfSeries(arr, function (x, i, callback) {
        iterator(memo, x, function (err, v) {
            memo = v;
            callback(err);
        });
    }, function (err) {
        callback(err, memo);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.foldr"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>foldr (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.foldr)
- description and source-code
```javascript
foldr = function (arr, memo, iterator, callback) {
    var reversed = _map(arr, identity).reverse();
    async.reduce(reversed, memo, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.forEach"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>forEach (arr, iterator, callback)](#apidoc.element.grunt.util.async.forEach)
- description and source-code
```javascript
forEach = function (arr, iterator, callback) {
    return async.eachOf(arr, _withoutIndex(iterator), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.forEachLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachLimit (arr, limit, iterator, callback)](#apidoc.element.grunt.util.async.forEachLimit)
- description and source-code
```javascript
forEachLimit = function (arr, limit, iterator, callback) {
    return _eachOfLimit(limit)(arr, _withoutIndex(iterator), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.forEachOf"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachOf (object, iterator, callback)](#apidoc.element.grunt.util.async.forEachOf)
- description and source-code
```javascript
forEachOf = function (object, iterator, callback) {
    callback = _once(callback || noop);
    object = object || [];

    var iter = _keyIterator(object);
    var key, completed = 0;

    while ((key = iter()) != null) {
        completed += 1;
        iterator(object[key], key, only_once(done));
    }

    if (completed === 0) callback(null);

    function done(err) {
        completed--;
        if (err) {
            callback(err);
        }
        // Check key is null in case iterator isn't exhausted
        // and done resolved synchronously.
        else if (key === null && completed <= 0) {
            callback(null);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.forEachOfLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachOfLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.forEachOfLimit)
- description and source-code
```javascript
forEachOfLimit = function (obj, limit, iterator, callback) {
    _eachOfLimit(limit)(obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.forEachOfSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachOfSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.forEachOfSeries)
- description and source-code
```javascript
forEachOfSeries = function (obj, iterator, callback) {
    callback = _once(callback || noop);
    obj = obj || [];
    var nextKey = _keyIterator(obj);
    var key = nextKey();
    function iterate() {
        var sync = true;
        if (key === null) {
            return callback(null);
        }
        iterator(obj[key], key, only_once(function (err) {
            if (err) {
                callback(err);
            }
            else {
                key = nextKey();
                if (key === null) {
                    return callback(null);
                } else {
                    if (sync) {
                        async.setImmediate(iterate);
                    } else {
                        iterate();
                    }
                }
            }
        }));
        sync = false;
    }
    iterate();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.forEachSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>forEachSeries (arr, iterator, callback)](#apidoc.element.grunt.util.async.forEachSeries)
- description and source-code
```javascript
forEachSeries = function (arr, iterator, callback) {
    return async.eachOfSeries(arr, _withoutIndex(iterator), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.forever"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>forever (fn, callback)](#apidoc.element.grunt.util.async.forever)
- description and source-code
```javascript
forever = function (fn, callback) {
    var done = only_once(callback || noop);
    var task = ensureAsync(fn);
    function next(err) {
        if (err) {
            return done(err);
        }
        task(next);
    }
    next();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.inject"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>inject (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.inject)
- description and source-code
```javascript
inject = function (arr, memo, iterator, callback) {
    async.eachOfSeries(arr, function (x, i, callback) {
        iterator(memo, x, function (err, v) {
            memo = v;
            callback(err);
        });
    }, function (err) {
        callback(err, memo);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.iterator"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>iterator (tasks)](#apidoc.element.grunt.util.async.iterator)
- description and source-code
```javascript
iterator = function (tasks) {
    function makeCallback(index) {
        function fn() {
            if (tasks.length) {
                tasks[index].apply(null, arguments);
            }
            return fn.next();
        }
        fn.next = function () {
            return (index < tasks.length - 1) ? makeCallback(index + 1): null;
        };
        return fn;
    }
    return makeCallback(0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.log"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>log ()](#apidoc.element.grunt.util.async.log)
- description and source-code
```javascript
log = function () {
    var length = Math.max(arguments.length - startIndex, 0);
    var rest = Array(length);
    for (var index = 0; index < length; index++) {
        rest[index] = arguments[index + startIndex];
    }
    switch (startIndex) {
        case 0: return func.call(this, rest);
        case 1: return func.call(this, arguments[0], rest);
    }
    // Currently unused but handle cases outside of the switch statement:
    // var args = Array(startIndex + 1);
    // for (index = 0; index < startIndex; index++) {
    //     args[index] = arguments[index];
    // }
    // args[startIndex] = rest;
    // return func.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.map"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>map (obj, iterator, callback)](#apidoc.element.grunt.util.async.map)
- description and source-code
```javascript
map = function (obj, iterator, callback) {
    return fn(async.eachOf, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.mapLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>mapLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.mapLimit)
- description and source-code
```javascript
mapLimit = function (obj, limit, iterator, callback) {
    return fn(_eachOfLimit(limit), obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.mapSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>mapSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.mapSeries)
- description and source-code
```javascript
mapSeries = function (obj, iterator, callback) {
    return fn(async.eachOfSeries, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.memoize"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>memoize (fn, hasher)](#apidoc.element.grunt.util.async.memoize)
- description and source-code
```javascript
memoize = function (fn, hasher) {
    var memo = {};
    var queues = {};
    var has = Object.prototype.hasOwnProperty;
    hasher = hasher || identity;
    var memoized = _restParam(function memoized(args) {
        var callback = args.pop();
        var key = hasher.apply(null, args);
        if (has.call(memo, key)) {
            async.setImmediate(function () {
                callback.apply(null, memo[key]);
            });
        }
        else if (has.call(queues, key)) {
            queues[key].push(callback);
        }
        else {
            queues[key] = [callback];
            fn.apply(null, args.concat([_restParam(function (args) {
                memo[key] = args;
                var q = queues[key];
                delete queues[key];
                for (var i = 0, l = q.length; i < l; i++) {
                    q[i].apply(null, args);
                }
            })]));
        }
    });
    memoized.memo = memo;
    memoized.unmemoized = fn;
    return memoized;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.nextTick"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>nextTick (callback)](#apidoc.element.grunt.util.async.nextTick)
- description and source-code
```javascript
function nextTick(callback) {
  if (typeof callback !== 'function')
    throw new TypeError('callback is not a function');
  // on the way out, don't bother. it won't get fired anyway.
  if (process._exiting)
    return;

  var args;
  if (arguments.length > 1) {
    args = new Array(arguments.length - 1);
    for (var i = 1; i < arguments.length; i++)
      args[i - 1] = arguments[i];
  }

  nextTickQueue.push({
    callback,
    domain: process.domain || null,
    args
  });
  tickInfo[kLength]++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.noConflict"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>noConflict ()](#apidoc.element.grunt.util.async.noConflict)
- description and source-code
```javascript
noConflict = function () {
    root.async = previous_async;
    return async;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.parallel"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>parallel (tasks, callback)](#apidoc.element.grunt.util.async.parallel)
- description and source-code
```javascript
parallel = function (tasks, callback) {
    _parallel(async.eachOf, tasks, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.parallelLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>parallelLimit (tasks, limit, callback)](#apidoc.element.grunt.util.async.parallelLimit)
- description and source-code
```javascript
parallelLimit = function (tasks, limit, callback) {
    _parallel(_eachOfLimit(limit), tasks, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.priorityQueue"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>priorityQueue (worker, concurrency)](#apidoc.element.grunt.util.async.priorityQueue)
- description and source-code
```javascript
priorityQueue = function (worker, concurrency) {

    function _compareTasks(a, b){
        return a.priority - b.priority;
    }

    function _binarySearch(sequence, item, compare) {
        var beg = -1,
            end = sequence.length - 1;
        while (beg < end) {
            var mid = beg + ((end - beg + 1) >>> 1);
            if (compare(item, sequence[mid]) >= 0) {
                beg = mid;
            } else {
                end = mid - 1;
            }
        }
        return beg;
    }

    function _insert(q, data, priority, callback) {
        if (callback != null && typeof callback !== "function") {
            throw new Error("task callback must be a function");
        }
        q.started = true;
        if (!_isArray(data)) {
            data = [data];
        }
        if(data.length === 0) {
            // call drain immediately if there are no tasks
            return async.setImmediate(function() {
                q.drain();
            });
        }
        _arrayEach(data, function(task) {
            var item = {
                data: task,
                priority: priority,
                callback: typeof callback === 'function' ? callback : noop
            };

            q.tasks.splice(_binarySearch(q.tasks, item, _compareTasks) + 1, 0, item);

            if (q.tasks.length === q.concurrency) {
                q.saturated();
            }
            async.setImmediate(q.process);
        });
    }

    // Start with a normal queue
    var q = async.queue(worker, concurrency);

    // Override push to accept second parameter representing priority
    q.push = function (data, priority, callback) {
        _insert(q, data, priority, callback);
    };

    // Remove unshift function
    delete q.unshift;

    return q;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.queue"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>queue (worker, concurrency)](#apidoc.element.grunt.util.async.queue)
- description and source-code
```javascript
queue = function (worker, concurrency) {
    var q = _queue(function (items, cb) {
        worker(items[0], cb);
    }, concurrency, 1);

    return q;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.reduce"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>reduce (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.reduce)
- description and source-code
```javascript
reduce = function (arr, memo, iterator, callback) {
    async.eachOfSeries(arr, function (x, i, callback) {
        iterator(memo, x, function (err, v) {
            memo = v;
            callback(err);
        });
    }, function (err) {
        callback(err, memo);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.reduceRight"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>reduceRight (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.reduceRight)
- description and source-code
```javascript
reduceRight = function (arr, memo, iterator, callback) {
    var reversed = _map(arr, identity).reverse();
    async.reduce(reversed, memo, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.reject"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>reject (obj, iterator, callback)](#apidoc.element.grunt.util.async.reject)
- description and source-code
```javascript
reject = function (obj, iterator, callback) {
    return fn(async.eachOf, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.rejectLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>rejectLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.rejectLimit)
- description and source-code
```javascript
rejectLimit = function (obj, limit, iterator, callback) {
    return fn(_eachOfLimit(limit), obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.rejectSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>rejectSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.rejectSeries)
- description and source-code
```javascript
rejectSeries = function (obj, iterator, callback) {
    return fn(async.eachOfSeries, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.retry"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>retry (times, task, callback)](#apidoc.element.grunt.util.async.retry)
- description and source-code
```javascript
retry = function (times, task, callback) {
    var DEFAULT_TIMES = 5;
    var DEFAULT_INTERVAL = 0;

    var attempts = [];

    var opts = {
        times: DEFAULT_TIMES,
        interval: DEFAULT_INTERVAL
    };

    function parseTimes(acc, t){
        if(typeof t === 'number'){
            acc.times = parseInt(t, 10) || DEFAULT_TIMES;
        } else if(typeof t === 'object'){
            acc.times = parseInt(t.times, 10) || DEFAULT_TIMES;
            acc.interval = parseInt(t.interval, 10) || DEFAULT_INTERVAL;
        } else {
            throw new Error('Unsupported argument type for \'times\': ' + typeof t);
        }
    }

    var length = arguments.length;
    if (length < 1 || length > 3) {
        throw new Error('Invalid arguments - must be either (task), (task, callback), (times, task) or (times, task, callback)');
    } else if (length <= 2 && typeof times === 'function') {
        callback = task;
        task = times;
    }
    if (typeof times !== 'function') {
        parseTimes(opts, times);
    }
    opts.callback = callback;
    opts.task = task;

    function wrappedTask(wrappedCallback, wrappedResults) {
        function retryAttempt(task, finalAttempt) {
            return function(seriesCallback) {
                task(function(err, result){
                    seriesCallback(!err || finalAttempt, {err: err, result: result});
                }, wrappedResults);
            };
        }

        function retryInterval(interval){
            return function(seriesCallback){
                setTimeout(function(){
                    seriesCallback(null);
                }, interval);
            };
        }

        while (opts.times) {

            var finalAttempt = !(opts.times-=1);
            attempts.push(retryAttempt(opts.task, finalAttempt));
            if(!finalAttempt && opts.interval > 0){
                attempts.push(retryInterval(opts.interval));
            }
        }

        async.series(attempts, function(done, data){
            data = data[data.length - 1];
            (wrappedCallback || opts.callback)(data.err, data.result);
        });
    }

    // If a callback is passed, run this as a controll flow
    return opts.callback ? wrappedTask() : wrappedTask;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.select"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>select (obj, iterator, callback)](#apidoc.element.grunt.util.async.select)
- description and source-code
```javascript
select = function (obj, iterator, callback) {
    return fn(async.eachOf, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.selectLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>selectLimit (obj, limit, iterator, callback)](#apidoc.element.grunt.util.async.selectLimit)
- description and source-code
```javascript
selectLimit = function (obj, limit, iterator, callback) {
    return fn(_eachOfLimit(limit), obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.selectSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>selectSeries (obj, iterator, callback)](#apidoc.element.grunt.util.async.selectSeries)
- description and source-code
```javascript
selectSeries = function (obj, iterator, callback) {
    return fn(async.eachOfSeries, obj, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.seq"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>seq ()](#apidoc.element.grunt.util.async.seq)
- description and source-code
```javascript
seq = function () {
    var fns = arguments;
    return _restParam(function (args) {
        var that = this;

        var callback = args[args.length - 1];
        if (typeof callback == 'function') {
            args.pop();
        } else {
            callback = noop;
        }

        async.reduce(fns, args, function (newargs, fn, cb) {
            fn.apply(that, newargs.concat([_restParam(function (err, nextargs) {
                cb(err, nextargs);
            })]));
        },
        function (err, results) {
            callback.apply(that, [err].concat(results));
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.series"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>series (tasks, callback)](#apidoc.element.grunt.util.async.series)
- description and source-code
```javascript
series = function (tasks, callback) {
    _parallel(async.eachOfSeries, tasks, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.setImmediate"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>setImmediate (fn)](#apidoc.element.grunt.util.async.setImmediate)
- description and source-code
```javascript
setImmediate = function (fn) {
    // not a direct alias for IE10 compatibility
    _setImmediate(fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.some"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>some (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.some)
- description and source-code
```javascript
some = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.someLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>someLimit (arr, limit, iterator, cb)](#apidoc.element.grunt.util.async.someLimit)
- description and source-code
```javascript
someLimit = function (arr, limit, iterator, cb) {
    function done() {
        if (cb) cb(getResult(false, void 0));
    }
    function iteratee(x, _, callback) {
        if (!cb) return callback();
        iterator(x, function (v) {
            if (cb && check(v)) {
                cb(getResult(true, x));
                cb = iterator = false;
            }
            callback();
        });
    }
    if (arguments.length > 3) {
        eachfn(arr, limit, iteratee, done);
    } else {
        cb = iterator;
        iterator = limit;
        eachfn(arr, iteratee, done);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.sortBy"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>sortBy (arr, iterator, callback)](#apidoc.element.grunt.util.async.sortBy)
- description and source-code
```javascript
sortBy = function (arr, iterator, callback) {
    async.map(arr, function (x, callback) {
        iterator(x, function (err, criteria) {
            if (err) {
                callback(err);
            }
            else {
                callback(null, {value: x, criteria: criteria});
            }
        });
    }, function (err, results) {
        if (err) {
            return callback(err);
        }
        else {
            callback(null, _map(results.sort(comparator), function (x) {
                return x.value;
            }));
        }

    });

    function comparator(left, right) {
        var a = left.criteria, b = right.criteria;
        return a < b ? -1 : a > b ? 1 : 0;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.times"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>times (count, iterator, callback)](#apidoc.element.grunt.util.async.times)
- description and source-code
```javascript
times = function (count, iterator, callback) {
    mapper(_range(count), iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.timesLimit"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>timesLimit (count, limit, iterator, callback)](#apidoc.element.grunt.util.async.timesLimit)
- description and source-code
```javascript
timesLimit = function (count, limit, iterator, callback) {
    return async.mapLimit(_range(count), limit, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.timesSeries"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>timesSeries (count, iterator, callback)](#apidoc.element.grunt.util.async.timesSeries)
- description and source-code
```javascript
timesSeries = function (count, iterator, callback) {
    mapper(_range(count), iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.transform"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>transform (arr, memo, iterator, callback)](#apidoc.element.grunt.util.async.transform)
- description and source-code
```javascript
transform = function (arr, memo, iterator, callback) {
    if (arguments.length === 3) {
        callback = iterator;
        iterator = memo;
        memo = _isArray(arr) ? [] : {};
    }

    async.eachOf(arr, function(v, k, cb) {
        iterator(memo, v, k, cb);
    }, function(err) {
        callback(err, memo);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.unmemoize"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>unmemoize (fn)](#apidoc.element.grunt.util.async.unmemoize)
- description and source-code
```javascript
unmemoize = function (fn) {
    return function () {
        return (fn.unmemoized || fn).apply(null, arguments);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.until"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>until (test, iterator, callback)](#apidoc.element.grunt.util.async.until)
- description and source-code
```javascript
until = function (test, iterator, callback) {
    return async.whilst(function() {
        return !test.apply(this, arguments);
    }, iterator, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.waterfall"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>waterfall (tasks, callback)](#apidoc.element.grunt.util.async.waterfall)
- description and source-code
```javascript
waterfall = function (tasks, callback) {
    callback = _once(callback || noop);
    if (!_isArray(tasks)) {
        var err = new Error('First argument to waterfall must be an array of functions');
        return callback(err);
    }
    if (!tasks.length) {
        return callback();
    }
    function wrapIterator(iterator) {
        return _restParam(function (err, args) {
            if (err) {
                callback.apply(null, [err].concat(args));
            }
            else {
                var next = iterator.next();
                if (next) {
                    args.push(wrapIterator(next));
                }
                else {
                    args.push(callback);
                }
                ensureAsync(iterator).apply(null, args);
            }
        });
    }
    wrapIterator(async.iterator(tasks))();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.whilst"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>whilst (test, iterator, callback)](#apidoc.element.grunt.util.async.whilst)
- description and source-code
```javascript
whilst = function (test, iterator, callback) {
    callback = callback || noop;
    if (test()) {
        var next = _restParam(function(err, args) {
            if (err) {
                callback(err);
            } else if (test.apply(this, args)) {
                iterator(next);
            } else {
                callback.apply(null, [null].concat(args));
            }
        });
        iterator(next);
    } else {
        callback(null);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.async.wrapSync"></a>[function <span class="apidocSignatureSpan">grunt.util.async.</span>wrapSync (func)](#apidoc.element.grunt.util.async.wrapSync)
- description and source-code
```javascript
function asyncify(func) {
    return _restParam(function (args) {
        var callback = args.pop();
        var result;
        try {
            result = func.apply(this, args);
        } catch (e) {
            return callback(e);
        }
        // if result is Promise object
        if (_isObject(result) && typeof result.then === "function") {
            result.then(function(value) {
                callback(null, value);
            })["catch"](function(err) {
                callback(err.message ? err : new Error(err));
            });
        } else {
            callback(null, result);
        }
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util.hooker"></a>[module grunt.util.hooker](#apidoc.module.grunt.util.hooker)

#### <a name="apidoc.element.grunt.util.hooker.filter"></a>[function <span class="apidocSignatureSpan">grunt.util.hooker.</span>filter (context, args)](#apidoc.element.grunt.util.hooker.filter)
- description and source-code
```javascript
filter = function (context, args) {
  return new HookerFilter(context, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.hooker.hook"></a>[function <span class="apidocSignatureSpan">grunt.util.hooker.</span>hook (obj, props, options)](#apidoc.element.grunt.util.hooker.hook)
- description and source-code
```javascript
hook = function (obj, props, options) {
  // If the props argument was omitted, shuffle the arguments.
  if (options == null) {
    options = props;
    props = null;
  }
  // If just a function is passed instead of an options hash, use that as a
  // pre-hook function.
  if (typeof options === "function") {
    options = {pre: options};
  }

  // Hook the specified method of the object.
  return forMethods(obj, props, function(obj, prop) {
    // The original (current) method.
    var orig = obj[prop];
    // The new hooked function.
    function hooked() {
      var result, origResult, tmp;

      // Get an array of arguments.
      var args = slice.call(arguments);

      // If passName option is specified, prepend prop to the args array,
      // passing it as the first argument to any specified hook functions.
      if (options.passName) {
        args.unshift(prop);
      }

      // If a pre-hook function was specified, invoke it in the current
      // context with the passed-in arguments, and store its result.
      if (options.pre) {
        result = options.pre.apply(this, args);
      }

      if (result instanceof HookerFilter) {
        // If the pre-hook returned hooker.filter(context, args), invoke the
        // original function with that context and arguments, and store its
        // result.
        origResult = result = orig.apply(result.context, result.args);
      } else if (result instanceof HookerPreempt) {
        // If the pre-hook returned hooker.preempt(value) just use the passed
        // value and don't execute the original function.
        origResult = result = result.value;
      } else {
        // Invoke the original function in the current context with the
        // passed-in arguments, and store its result.
        origResult = orig.apply(this, arguments);
        // If the pre-hook returned hooker.override(value), use the passed
        // value, otherwise use the original function's result.
        result = result instanceof HookerOverride ? result.value : origResult;
      }

      if (options.post) {
        // If a post-hook function was specified, invoke it in the current
        // context, passing in the result of the original function as the
        // first argument, followed by any passed-in arguments.
        tmp = options.post.apply(this, [origResult].concat(args));
        if (tmp instanceof HookerOverride) {
          // If the post-hook returned hooker.override(value), use the passed
          // value, otherwise use the previously computed result.
          result = tmp.value;
        }
      }

      // Unhook if the "once" option was specified.
      if (options.once) {
        exports.unhook(obj, prop);
      }

      // Return the result!
      return result;
    }
    // Re-define the method.
    obj[prop] = hooked;
    // Fail if the function couldn't be hooked.
    if (obj[prop] !== hooked) { return false; }
    // Store a reference to the original method as a property on the new one.
    obj[prop]._orig = orig;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.hooker.orig"></a>[function <span class="apidocSignatureSpan">grunt.util.hooker.</span>orig (obj, prop)](#apidoc.element.grunt.util.hooker.orig)
- description and source-code
```javascript
orig = function (obj, prop) {
  return obj[prop]._orig;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.hooker.override"></a>[function <span class="apidocSignatureSpan">grunt.util.hooker.</span>override (value)](#apidoc.element.grunt.util.hooker.override)
- description and source-code
```javascript
override = function (value) {
  return new HookerOverride(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.hooker.preempt"></a>[function <span class="apidocSignatureSpan">grunt.util.hooker.</span>preempt (value)](#apidoc.element.grunt.util.hooker.preempt)
- description and source-code
```javascript
preempt = function (value) {
  return new HookerPreempt(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.hooker.unhook"></a>[function <span class="apidocSignatureSpan">grunt.util.hooker.</span>unhook (obj, props)](#apidoc.element.grunt.util.hooker.unhook)
- description and source-code
```javascript
unhook = function (obj, props) {
  return forMethods(obj, props, function(obj, prop) {
    // Get a reference to the original method, if it exists.
    var orig = exports.orig(obj, prop);
    // If there's no original method, it can't be unhooked, so fail.
    if (!orig) { return false; }
    // Unhook the method.
    obj[prop] = orig;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util.namespace"></a>[module grunt.util.namespace](#apidoc.module.grunt.util.namespace)

#### <a name="apidoc.element.grunt.util.namespace.exists"></a>[function <span class="apidocSignatureSpan">grunt.util.namespace.</span>exists (obj, parts)](#apidoc.element.grunt.util.namespace.exists)
- description and source-code
```javascript
exists = function (obj, parts) {
  parts = getParts(parts);

  var prop = parts.pop();
  obj = getobject.get(obj, parts);

  return typeof obj === 'object' && obj && prop in obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.namespace.get"></a>[function <span class="apidocSignatureSpan">grunt.util.namespace.</span>get (obj, parts, create)](#apidoc.element.grunt.util.namespace.get)
- description and source-code
```javascript
get = function (obj, parts, create) {
  if (typeof parts === 'string') {
    parts = getParts(parts);
  }

  var part;
  while (typeof obj === 'object' && obj && parts.length) {
    part = parts.shift();
    if (!(part in obj) && create) {
      obj[part] = {};
    }
    obj = obj[part];
  }

  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.namespace.set"></a>[function <span class="apidocSignatureSpan">grunt.util.namespace.</span>set (obj, parts, value)](#apidoc.element.grunt.util.namespace.set)
- description and source-code
```javascript
set = function (obj, parts, value) {
  parts = getParts(parts);

  var prop = parts.pop();
  obj = getobject.get(obj, parts, true);
  if (obj && typeof obj === 'object') {
    return (obj[prop] = value);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util.task"></a>[module grunt.util.task](#apidoc.module.grunt.util.task)

#### <a name="apidoc.element.grunt.util.task.Task"></a>[function <span class="apidocSignatureSpan">grunt.util.task.</span>Task ()](#apidoc.element.grunt.util.task.Task)
- description and source-code
```javascript
function Task() {
  // Information about the currently-running task.
  this.current = {};
  // Tasks.
  this._tasks = {};
  // Task queue.
  this._queue = [];
  // Queue placeholder (for dealing with nested tasks).
  this._placeholder = {placeholder: true};
  // Queue marker (for clearing the queue programmatically).
  this._marker = {marker: true};
  // Options.
  this._options = {};
  // Is the queue running?
  this._running = false;
  // Success status of completed tasks.
  this._success = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.create"></a>[function <span class="apidocSignatureSpan">grunt.util.task.</span>create ()](#apidoc.element.grunt.util.task.create)
- description and source-code
```javascript
create = function () {
  return new Task();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.util.task.Task.prototype"></a>[module grunt.util.task.Task.prototype](#apidoc.module.grunt.util.task.Task.prototype)

#### <a name="apidoc.element.grunt.util.task.Task.prototype._push"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>_push (things)](#apidoc.element.grunt.util.task.Task.prototype._push)
- description and source-code
```javascript
_push = function (things) {
  // Get current placeholder index.
  var index = this._queue.indexOf(this._placeholder);
  if (index === -1) {
    // No placeholder, add task+args objects to end of queue.
    this._queue = this._queue.concat(things);
  } else {
    // Placeholder exists, add task+args objects just before placeholder.
    [].splice.apply(this._queue, [index, 0].concat(things));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype._taskPlusArgs"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>_taskPlusArgs (name)](#apidoc.element.grunt.util.task.Task.prototype._taskPlusArgs)
- description and source-code
```javascript
_taskPlusArgs = function (name) {
  // Get task name / argument parts.
  var parts = this.splitArgs(name);
  // Start from the end, not the beginning!
  var i = parts.length;
  var task;
  do {
    // Get a task.
    task = this._tasks[parts.slice(0, i).join(':')];
    // If the task doesn't exist, decrement 'i', and if 'i' is greater than
    // 0, repeat.
  } while (!task && --i > 0);
  // Just the args.
  var args = parts.slice(i);
  // Maybe you want to use them as flags instead of as positional args?
  var flags = {};
  args.forEach(function(arg) { flags[arg] = true; });
  // The task to run and the args to run it with.
  return {task: task, nameArgs: name, args: args, flags: flags};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype._throwIfRunning"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>_throwIfRunning (obj)](#apidoc.element.grunt.util.task.Task.prototype._throwIfRunning)
- description and source-code
```javascript
_throwIfRunning = function (obj) {
  if (this._running || !this._options.error) {
    // Throw an exception that the task runner will catch.
    throw obj;
  } else {
    // Not inside the task runner. Call the error handler and abort.
    this._options.error.call({name: null}, obj);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.clearQueue"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>clearQueue (options)](#apidoc.element.grunt.util.task.Task.prototype.clearQueue)
- description and source-code
```javascript
clearQueue = function (options) {
  if (!options) { options = {}; }
  if (options.untilMarker) {
    this._queue.splice(0, this._queue.indexOf(this._marker) + 1);
  } else {
    this._queue = [];
  }
  // Make chainable!
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.exists"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>exists (name)](#apidoc.element.grunt.util.task.Task.prototype.exists)
- description and source-code
```javascript
exists = function (name) {
  return name in this._tasks;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.isTaskAlias"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>isTaskAlias (name)](#apidoc.element.grunt.util.task.Task.prototype.isTaskAlias)
- description and source-code
```javascript
isTaskAlias = function (name) {
  return !!this._tasks[name].fn.alias;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.mark"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>mark ()](#apidoc.element.grunt.util.task.Task.prototype.mark)
- description and source-code
```javascript
mark = function () {
  this._push(this._marker);
  // Make chainable!
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.options"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>options (options)](#apidoc.element.grunt.util.task.Task.prototype.options)
- description and source-code
```javascript
options = function (options) {
  Object.keys(options).forEach(function(name) {
    this._options[name] = options[name];
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.parseArgs"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>parseArgs (args)](#apidoc.element.grunt.util.task.Task.prototype.parseArgs)
- description and source-code
```javascript
parseArgs = function (args) {
  // Return the first argument if it's an array, otherwise return an array
  // of all arguments.
  return Array.isArray(args[0]) ? args[0] : [].slice.call(args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.registerTask"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>registerTask (name, info, fn)](#apidoc.element.grunt.util.task.Task.prototype.registerTask)
- description and source-code
```javascript
registerTask = function (name, info, fn) {
  // If optional "info" string is omitted, shuffle arguments a bit.
  if (fn == null) {
    fn = info;
    info = null;
  }
  // String or array of strings was passed instead of fn.
  var tasks;
  if (typeof fn !== 'function') {
    // Array of task names.
    tasks = this.parseArgs([fn]);
    // This task function just runs the specified tasks.
    fn = this.run.bind(this, fn);
    fn.alias = true;
    // Generate an info string if one wasn't explicitly passed.
    if (!info) {
      info = 'Alias for "' + tasks.join('", "') + '" task' +
        (tasks.length === 1 ? '' : 's') + '.';
    }
  } else if (!info) {
    info = 'Custom task.';
  }
  // Add task into cache.
  this._tasks[name] = {name: name, info: info, fn: fn};
  // Make chainable!
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.renameTask"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>renameTask (oldname, newname)](#apidoc.element.grunt.util.task.Task.prototype.renameTask)
- description and source-code
```javascript
renameTask = function (oldname, newname) {
  if (!this._tasks[oldname]) {
    throw new Error('Cannot rename missing "' + oldname + '" task.');
  }
  // Rename task.
  this._tasks[newname] = this._tasks[oldname];
  // Update name property of task.
  this._tasks[newname].name = newname;
  // Remove old name.
  delete this._tasks[oldname];
  // Make chainable!
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.requires"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>requires ()](#apidoc.element.grunt.util.task.Task.prototype.requires)
- description and source-code
```javascript
requires = function () {
  this.parseArgs(arguments).forEach(function(name) {
    var success = this._success[name];
    if (!success) {
      throw new Error('Required task "' + name +
        '" ' + (success === false ? 'failed' : 'must be run first') + '.');
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.run"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>run ()](#apidoc.element.grunt.util.task.Task.prototype.run)
- description and source-code
```javascript
run = function () {
  // Parse arguments into an array, returning an array of task+args objects.
  var things = this.parseArgs(arguments).map(this._taskPlusArgs, this);
  // Throw an exception if any tasks weren't found.
  var fails = things.filter(function(thing) { return !thing.task; });
  if (fails.length > 0) {
    this._throwIfRunning(new Error('Task "' + fails[0].nameArgs + '" not found.'));
    return this;
  }
  // Append things to queue in the correct spot.
  this._push(things);
  // Make chainable!
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.runTaskFn"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>runTaskFn (context, fn, done, asyncDone)](#apidoc.element.grunt.util.task.Task.prototype.runTaskFn)
- description and source-code
```javascript
runTaskFn = function (context, fn, done, asyncDone) {
  // Async flag.
  var async = false;

  // Update the internal status object and run the next task.
  var complete = function(success) {
    var err = null;
    if (success === false) {
      // Since false was passed, the task failed generically.
      err = new Error('Task "' + context.nameArgs + '" failed.');
    } else if (success instanceof Error || {}.toString.call(success) === '[object Error]') {
      // An error object was passed, so the task failed specifically.
      err = success;
      success = false;
    } else {
      // The task succeeded.
      success = true;
    }
    // The task has ended, reset the current task object.
    this.current = {};
    // A task has "failed" only if it returns false (async) or if the
    // function returned by .async is passed false.
    this._success[context.nameArgs] = success;
    // If task failed, call error handler.
    if (!success && this._options.error) {
      this._options.error.call({name: context.name, nameArgs: context.nameArgs}, err);
    }
    // only call done async if explicitly requested to
    // see: https://github.com/gruntjs/grunt/pull/1026
    if (asyncDone) {
      process.nextTick(function() {
        done(err, success);
      });
    } else {
      done(err, success);
    }
  }.bind(this);

  // When called, sets the async flag and returns a function that can
  // be used to continue processing the queue.
  context.async = function() {
    async = true;
    // The returned function should execute asynchronously in case
    // someone tries to do this.async()(); inside a task (WTF).
    return grunt.util._.once(function(success) {
      setTimeout(function() { complete(success); }, 1);
    });
  };

  // Expose some information about the currently-running task.
  this.current = context;

  try {
    // Get the current task and run it, setting 'this' inside the task
    // function to be something useful.
    var success = fn.call(context);
    // If the async flag wasn't set, process the next task in the queue.
    if (!async) {
      complete(success);
    }
  } catch (err) {
    complete(err);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.splitArgs"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>splitArgs (str)](#apidoc.element.grunt.util.task.Task.prototype.splitArgs)
- description and source-code
```javascript
splitArgs = function (str) {
  if (!str) { return []; }
  // Store placeholder for \\ followed by \:
  str = str.replace(/\\\\/g, '\uFFFF').replace(/\\:/g, '\uFFFE');
  // Split on :
  return str.split(':').map(function(s) {
    // Restore place-held : followed by \\
    return s.replace(/\uFFFE/g, ':').replace(/\uFFFF/g, '\\');
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.util.task.Task.prototype.start"></a>[function <span class="apidocSignatureSpan">grunt.util.task.Task.prototype.</span>start (opts)](#apidoc.element.grunt.util.task.Task.prototype.start)
- description and source-code
```javascript
start = function (opts) {
  if (!opts) {
    opts = {};
  }
  // Abort if already running.
  if (this._running) { return false; }
  // Actually process the next task.
  var nextTask = function() {
    // Get next task+args object from queue.
    var thing;
    // Skip any placeholders or markers.
    do {
      thing = this._queue.shift();
    } while (thing === this._placeholder || thing === this._marker);
    // If queue was empty, we're all done.
    if (!thing) {
      this._running = false;
      if (this._options.done) {
        this._options.done();
      }
      return;
    }
    // Add a placeholder to the front of the queue.
    this._queue.unshift(this._placeholder);

    // Expose some information about the currently-running task.
    var context = {
      // The current task name plus args, as-passed.
      nameArgs: thing.nameArgs,
      // The current task name.
      name: thing.task.name,
      // The current task arguments.
      args: thing.args,
      // The current arguments, available as named flags.
      flags: thing.flags
    };

    // Actually run the task function (handling this.async, etc)
    this.runTaskFn(context, function() {
      return thing.task.fn.apply(this, this.args);
    }, nextTask, !!opts.asyncDone);

  }.bind(this);

  // Update flag.
  this._running = true;
  // Process the next task.
  nextTask();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt.verbose"></a>[module grunt.verbose](#apidoc.module.grunt.verbose)

#### <a name="apidoc.element.grunt.verbose._format"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>_format ()](#apidoc.element.grunt.verbose._format)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose._markup"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>_markup ()](#apidoc.element.grunt.verbose._markup)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose._write"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>_write ()](#apidoc.element.grunt.verbose._write)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose._writeln"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>_writeln ()](#apidoc.element.grunt.verbose._writeln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.debug"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>debug ()](#apidoc.element.grunt.verbose.debug)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.error"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>error ()](#apidoc.element.grunt.verbose.error)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.errorlns"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>errorlns ()](#apidoc.element.grunt.verbose.errorlns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.fail"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>fail ()](#apidoc.element.grunt.verbose.fail)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.header"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>header ()](#apidoc.element.grunt.verbose.header)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.initColors"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>initColors ()](#apidoc.element.grunt.verbose.initColors)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.ok"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>ok ()](#apidoc.element.grunt.verbose.ok)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.oklns"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>oklns ()](#apidoc.element.grunt.verbose.oklns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.option"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>option ()](#apidoc.element.grunt.verbose.option)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.subhead"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>subhead ()](#apidoc.element.grunt.verbose.subhead)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.success"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>success ()](#apidoc.element.grunt.verbose.success)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.table"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>table ()](#apidoc.element.grunt.verbose.table)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.uncolor"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>uncolor ()](#apidoc.element.grunt.verbose.uncolor)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.warn"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>warn ()](#apidoc.element.grunt.verbose.warn)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.wordlist"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>wordlist ()](#apidoc.element.grunt.verbose.wordlist)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.wraptext"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>wraptext ()](#apidoc.element.grunt.verbose.wraptext)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.write"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>write ()](#apidoc.element.grunt.verbose.write)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.writeflags"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>writeflags ()](#apidoc.element.grunt.verbose.writeflags)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.writeln"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>writeln ()](#apidoc.element.grunt.verbose.writeln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.writelns"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>writelns ()](#apidoc.element.grunt.verbose.writelns)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt.verbose.writetableln"></a>[function <span class="apidocSignatureSpan">grunt.verbose.</span>writetableln ()](#apidoc.element.grunt.verbose.writetableln)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
