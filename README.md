VSCode Server and related stuff for Alpine Linux

**Server Version:**
- Alpine v3.6.9

**Working (tested) Nodejs versions available:**
- v20.18.3 (build on listed alpine version)
- v19.9.0 (build on listed alpine version)
- v16.8.1

**Not working Nodejs versions:**
- v21.7.3  (build successfully on listed alpine version; unable to run)
- v18.20.7 (build successfully on listed alpine version; failed at `code-server --version`)
- v18.20.4 (build successfully on listed alpine version; failed at `code-server --version`)

**Failed to build:**
- ^v23 (needs python ^3.8.0)
- ^v22 (needs python ^3.8.0)

**Settings used for building:**\
`--with-intl=small-icu`

**Documentation:**\
https://github.com/nodejs/node/blob/main/BUILDING.md
