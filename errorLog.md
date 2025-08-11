12:36:26 PM: buildbot version: 72ba091da8478e084b7407a21cd8435e7ecab808
12:36:26 PM: build-image version: 71a98eb82b055b934e7d58946f59957e90f5a76f (noble)
12:36:27 PM: Fetching cached dependencies
12:36:27 PM: Failed to fetch cache, continuing with build
12:36:27 PM: Starting to prepare the repo for build
12:36:27 PM: No cached dependencies found. Cloning fresh repo
12:36:27 PM: git clone --filter=blob:none https://github.com/notj-code/GYMBROS_download_page
12:36:27 PM: Preparing Git Reference refs/heads/main
12:36:29 PM: Starting to install dependencies
12:36:30 PM: v22.18.0 is already installed.
12:36:30 PM: Now using node v22.18.0 (npm v10.9.3)
12:36:30 PM: Enabling Node.js Corepack
12:36:30 PM: Started restoring cached build plugins
12:36:30 PM: Finished restoring cached build plugins
12:36:30 PM: Successfully installed dependencies
12:36:30 PM: Starting build script
12:36:31 PM: Detected 1 framework(s)
12:36:31 PM: "jekyll" at version "unknown"
12:36:31 PM: Section completed: initializing
12:36:32 PM: ​
12:36:32 PM: Netlify Build                                                 
12:36:32 PM: ────────────────────────────────────────────────────────────────
12:36:32 PM: ​
12:36:32 PM: ❯ Version
12:36:32 PM:   @netlify/build 35.0.5
12:36:32 PM: ​
12:36:32 PM: ❯ Flags
12:36:32 PM:   accountId: 6597baa848019a980272ce02
12:36:32 PM:   baseRelDir: true
12:36:32 PM:   buildId: 68996507c7658b37b0fc432f
12:36:32 PM:   deployId: 68996507c7658b37b0fc4331
12:36:32 PM: ​
12:36:32 PM: ❯ Current directory
12:36:32 PM:   /opt/build/repo
12:36:32 PM: ​
12:36:32 PM: ❯ Config file
12:36:32 PM:   No config file was defined: using default values.
12:36:32 PM: ​
12:36:32 PM: ❯ Context
12:36:32 PM:   production
12:36:32 PM: ​
12:36:32 PM: Build command from Netlify app                                
12:36:32 PM: ────────────────────────────────────────────────────────────────
12:36:32 PM: ​
12:36:32 PM: $ bundle exec jekyll build
12:36:32 PM: Could not locate Gemfile or .bundle/ directory
12:36:32 PM: ​
12:36:32 PM: "build.command" failed                                        
12:36:32 PM: ────────────────────────────────────────────────────────────────
12:36:32 PM: ​
12:36:32 PM:   Error message
12:36:32 PM:   Command failed with exit code 10: bundle exec jekyll build (https://ntl.fyi/exit-code-10)
12:36:32 PM: ​
12:36:32 PM:   Error location
12:36:32 PM:   In Build command from Netlify app:
12:36:32 PM:   bundle exec jekyll build
12:36:32 PM: ​
12:36:32 PM:   Resolved config
12:36:32 PM:   build:
12:36:32 PM:     command: bundle exec jekyll build
12:36:32 PM:     commandOrigin: ui
12:36:32 PM:     publish: /opt/build/repo/_site
12:36:32 PM:     publishOrigin: ui
12:36:33 PM: Failed during stage 'building site': Build script returned non-zero exit code: 2 (https://ntl.fyi/exit-code-2)
12:36:33 PM: Build failed due to a user error: Build script returned non-zero exit code: 2
12:36:33 PM: Failing build: Failed to build site
12:36:33 PM: Finished processing build request in 6.621s