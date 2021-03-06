---
date: 2015-12-16T09:24:56-07:00
title: "hugo benchmark"
slug: hugo_benchmark
url: /commands/hugo_benchmark/
---
## hugo benchmark

Benchmark hugo by building a site a number of times.

### Synopsis


Hugo can build a site many times over and analyze the running process
creating a benchmark.

```
hugo benchmark
```

### Options

```
  -b, --baseURL="": hostname (and path) to the root, e.g. http://spf13.com/
  -D, --buildDrafts[=false]: include content marked as draft
  -F, --buildFuture[=false]: include content with publishdate in the future
      --cacheDir="": filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/
      --canonifyURLs[=false]: if true, all relative URLs will be canonicalized using baseURL
      --config="": config file (default is path/config.yaml|json|toml)
  -n, --count=13: number of times to build the site
      --cpuprofile="": path/filename for the CPU profile file
  -d, --destination="": filesystem path to write files to
      --disableRSS[=false]: Do not build RSS files
      --disableSitemap[=false]: Do not build Sitemap file
      --editor="": edit new content with this editor, if provided
      --ignoreCache[=false]: Ignores the cache directory for reading but still writes to it
      --memprofile="": path/filename for the memory profile file
      --pluralizeListTitles[=true]: Pluralize titles in lists using inflect
      --preserveTaxonomyNames[=false]: Preserve taxonomy names as written ("Gérard Depardieu" vs "gerard-depardieu")
  -s, --source="": filesystem path to read files relative from
      --stepAnalysis[=false]: display memory and timing of different steps of the program
  -t, --theme="": theme to use (located in /themes/THEMENAME/)
      --uglyURLs[=false]: if true, use /filename.html instead of /filename/
```

### Options inherited from parent commands

```
      --log[=false]: Enable Logging
      --logFile="": Log File path (if set, logging enabled automatically)
  -v, --verbose[=false]: verbose output
      --verboseLog[=false]: verbose logging
```

### SEE ALSO
* [hugo](/commands/hugo/)	 - hugo builds your site

###### Auto generated by spf13/cobra on 16-Dec-2015
