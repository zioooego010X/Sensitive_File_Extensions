# Sensitive_File_Extensions
Sensitive File Extensions names

___________________________________
# 🗂️ File Extensions Categorized by Type

## 🌐 Web Files
- `.html`, `.htm`, `.xhtml`, `.shtml`
- `.php`, `.php3`, `.php4`, `.php5`, `.php7`, `.phtml`
- `.asp`, `.aspx`, `.ascx`, `.ashx`, `.asmx`
- `.jsp`, `.jspx`, `.do`, `.action`
- `.cfm`
- `.cgi`, `.pl`
- `.rhtml`, `.erb`
- `.ejs`, `.hbs`, `.twig`, `.mustache`, `.pug`, `.tt`

---

## 💻 Programming & Scripting Files
- **JavaScript**: `.js`, `.mjs`
- **TypeScript**: `.ts`, `.tsx`
- **React**: `.jsx`
- **Vue**: `.vue`
- **Svelte**: `.svelte`
- **CoffeeScript**: `.coffee`
- **Python**: `.py`, `.pyw`
- **Ruby**: `.rb`
- **Perl**: `.pl`, `.pm`
- **Shell Scripts**: `.sh`, `.bash`, `.zsh`
- **Batch Files**: `.bat`, `.cmd`
- **PowerShell**: `.ps1`
- **Go**: `.go`
- **Java**: `.java`, `.class`, `.jar`
- **C/C++**: `.c`, `.cpp`, `.cc`, `.cxx`, `.h`, `.hpp`
- **C#**: `.cs`
- **VBScript**: `.vbs`
- **Windows Script Files**: `.wsf`
- **Lua**: `.lua`
- **Rust**: `.rs`
- **Kotlin**: `.kt`, `.kts`
- **Swift**: `.swift`
- **Dart**: `.dart`
- **Scala**: `.scala`
- **Objective-C**: `.m`, `.mm`
- **Haskell**: `.hs`
- **Erlang**: `.erl`
- **Elixir**: `.ex`, `.exs`
- **R**: `.r`
- **Julia**: `.jl`
- **Groovy**: `.groovy`
- **Tcl**: `.tcl`
- **MATLAB**: `.m`
- **SQL**: `.sql`
- **Terraform**: `.tf`
- **Docker**: `Dockerfile`

---

## 🧾 Data Files
- `.json`
- `.yaml`, `.yml`
- `.xml`, `.rss`, `.atom`
- `.csv`, `.tsv`
- `.xls`, `.xlsx`
- `.parquet`, `.avro`, `.proto`, `.msgpack`, `.geojson`, `.bson`
- `.pickle`, `.mat`, `.nc`, `.sqldump`

---

## ⚙️ Text & Configuration Files
- `.txt`, `.md`, `.markdown`, `.rst`, `.adoc`, `.asciidoc`
- `.conf`, `.properties`, `.ini`, `.log`, `.config`
- `.gitignore`, `.dockerignore`, `.env`, `.lock`
- `.toml`, `.config.xml`
- `.editorconfig`, `.prettierrc`, `.eslintrc`
- `.travis.yml`, `.circleci/config.yml`

---

## 🖼️ Image Files
- `.png`, `.jpg`, `.jpeg`, `.gif`, `.bmp`, `.tif`, `.tiff`
- `.webp`, `.ico`, `.svg`, `.psd`, `.ai`, `.raw`, `.cr2`, `.nef`, `.arw`
- `.hdr`, `.xcf`

---

## 🔊 Audio Files
- `.mp3`, `.flac`, `.aac`, `.wav`, `.ogg`, `.m4a`, `.wma`
- `.aiff`, `.alac`, `.pcm`, `.opus`

---

## 🎥 Video Files
- `.mp4`, `.mov`, `.mkv`, `.avi`, `.flv`, `.webm`, `.wmv`, `.3gp`
- `.mpeg`, `.mpg`, `.ogv`, `.qt`, `.vob`, `.asf`

---

## 📄 Document Files
- `.pdf`, `.doc`, `.docx`, `.xls`, `.xlsx`, `.ppt`, `.pptx`
- `.odt`, `.ods`, `.odp`, `.rtf`, `.epub`, `.mobi`, `.tex`, `.ps`, `.djvu`

---

## 🧩 Backup & Temp Files
- `.bak`, `.backup`, `.old`, `.tmp`, `.temp`, `.~*`, `.#*`, `.snapshot`, `.orig`

---

## 🗜️ Compressed & Archive Files
- `.zip`, `.tar`, `.gz`, `.tgz`, `.bz2`, `.rar`, `.7z`, `.xz`, `.iso`, `.lzma`, `.Z`
- `.chm`, `.arj`, `.cab`, `.sit`, `.uue`

---

## 🛢️ Database Files
- `.db`, `.sqlite`, `.sql`, `.sqldump`, `.mdb`, `.accdb`, `.frm`, `.ibd`
- `.dat`, `.dbf`, `.rdb`, `.bdb`, `.fdb`, `.h2.db`

---

## 🔐 Security & Certificate Files
- `.pem`, `.crt`, `.cer`, `.key`, `.pfx`, `.p12`, `.der`, `.csr`, `.jks`, `.pk8`

---

## ⚙️ System & Project Files
- `.htaccess`, `.htpasswd`, `.git`, `.gitignore`, `.gitattributes`, `.svn`
- `.env`, `.env.local`, `.lock`, `.idea`, `.vscode`, `.editorconfig`
- `.travis.yml`, `.circleci`, `.github/workflows/*.yml`
- `Dockerfile`, `.dockerignore`
- `node_modules/`, `vendor/`, `build/`
- `Thumbs.db`, `.DS_Store`, `.containerfile`
___________________________________________________________________________________


| Category                     | Keywords to Search For                                                                                                                                                                                                                        | Description                                                   |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| 🔑 **API Keys / Secrets**    | `apiKey`, `apikey`, `api_key`, `secret`, `access_token`, `authToken`, `jwt`, `token`, `bearer`, `Authorization`, `client_secret`, `client_id`, `aws_access_key_id`, `aws_secret_access_key`, `private_key`, `consumer_key`, `consumer_secret` | Look for hardcoded credentials and auth tokens                |
| 🔐 **Authentication**        | `username`, `password`, `auth`, `authenticate`, `login`, `logout`, `session`, `cookie`, `csrf`, `csrfToken`, `xsrf`, `sso`, `otp`, `mfa`, `bearerToken`                                                                                       | May reveal authentication flow or session logic               |
| 🌐 **URLs / Endpoints**      | `url`, `endpoint`, `redirect`, `uri`, `nextUrl`, `callback`, `redirect_uri`, `host`, `baseUrl`, `http`, `https`, `internal_url`, `internal_api`, `admin`, `debug`, `dev`, `staging`                                                           | May expose hidden routes, open redirects, SSRF targets        |
| 🧾 **Configuration / Env**   | `config`, `configuration`, `settings`, `env`, `environment`, `debug`, `development`, `production`, `test`, `basePath`, `buildConfig`, `featureFlags`, `NODE_ENV`                                                                              | Can reveal debug info or sensitive environment setup          |
| 🔒 **Encryption / Keys**     | `key`, `encryptionKey`, `publicKey`, `privateKey`, `cipher`, `aes`, `rsa`, `hmac`, `hash`, `salt`, `bcrypt`, `md5`, `sha1`, `sha256`                                                                                                          | May reveal sensitive cryptographic details or weak algorithms |
| 💳 **Financial / Payment**   | `stripe`, `paypal`, `creditcard`, `cardNumber`, `cvc`, `payment`, `billing`, `iban`, `account_number`, `bank`, `transfer`, `invoice`                                                                                                          | May indicate payment flows or leaks                           |
| 📡 **Third-Party Services**  | `google`, `firebase`, `sentry`, `segment`, `datadog`, `amplitude`, `bugsnag`, `hotjar`, `mixpanel`, `intercom`, `auth0`, `okta`, `cloudflare`, `newrelic`                                                                                     | Watch for integrations leaking keys or tracking IDs           |
| 🧠 **Sensitive Logic**       | `isAdmin`, `admin`, `userRole`, `permissions`, `access`, `canEdit`, `canDelete`, `isAuthorized`, `isSuperUser`, `checkPermission`, `isRoot`                                                                                                   | Logic flaws may lead to privilege escalation                  |
| 🗃️ **Storage / Cache**      | `localStorage`, `sessionStorage`, `cookie`, `cache`, `rememberMe`, `storeToken`, `storageKey`, `saveToken`                                                                                                                                    | Tokens in storage can lead to XSS → account takeover          |
| 🛠️ **Debug / Internal Use** | `debug`, `console.log`, `console.error`, `trace`, `dump`, `window.__REACT_DEVTOOLS_GLOBAL_HOOK__`, `__debug__`, `__DEV__`, `__TEST__`                                                                                                         | Debug leftovers might leak info or be abused                  |
| 💬 **Comments / TODOs**      | `// TODO`, `// FIXME`, `// HACK`, `// BUG`, `/* secret */`, `// internal`, `// temp`, `// private`                                                                                                                                            | Dev comments might reveal unimplemented or sensitive info     |
| 🎯 **Hardcoded Data**        | `email`, `phone`, `mobile`, `address`, `ssn`, `passport`, `userData`, `personalInfo`, `contact`, `location`                                                                                                                                   | Look for PII or user data that shouldn’t be exposed           |

_______________________________
usfel search method :
1. grep
2. your own scripts
3. Dork : google , duck,duck,go
_______________________________
usfel tool 
1. burpsuite
2. SecretFinder
3. LinkFinder
4. TruffleHog
5. gf with custom patterns
6. dorksearch.com
7. GHDB
_________________________________________________________________________________________________

```


---

##  📄 what is in JavaScript Files

JavaScript files are often full of useful intel, especially hardcoded secrets or endpoint references.

- `apiKey`, `authToken`, `secret`, `access_token`, `client_secret`
- Firebase Configs
- AWS keys
- Debug logic and tokens


```
```

---

## . ⚙️ `.env` Files

Environment variable files can leak:

- `DB_PASSWORD`
- `JWT_SECRET`
- `AWS_SECRET_ACCESS_KEY`
- `EMAIL_PASSWORD`, etc.
```
```
---

## . 💾 Backup or Old Files

Sensitive configuration files are often left with unsafe backup names.

**Common extensions:**
- `.bak`, `.old`, `.backup`, `.tmp`, `.zip`, `.tar.gz`, `.rar`

```
````

---

## . ⚙️ Configuration Files

Configuration files might expose secrets, tokens, or access endpoints.

**Common files:**
- `config.js`, `config.json`
- `settings.py`, `firebase.js`
- `aws-exports.js`

---

## . 🧬 Git Repository Leaks

If the `.git/` folder is exposed, it's possible to reconstruct the full Git repo.

**Look for:**
- `.git/config`
- `.git/HEAD`
- `.git/index`

**Tools:**
- [GitTools](https://github.com/internetwache/GitTools)
- [git-dumper](https://github.com/arthaud/git-dumper)

---

## . 🌍 Public GitHub/GitLab/Bitbucket Repositories

Secrets can be exposed via public version control.

**How to search:**
- GitHub dorks (`filename:.env` OR `filename:config.js`)
- Use tools like:
  - `truffleHog`
  - `gitleaks`

---

## . 🧾 API Documentation Files

API documentation may contain keys or sensitive routes.

**Look for:**
- `swagger.json`
- `openapi.json`
- `postman_collection.json`

---

## . 💬 Comments in Code or HTML

Developers may leave hardcoded keys, tokens, or debug info in comments.

```html
<!-- TODO: Remove before production -->
<!-- API_KEY = "abc123" -->
````
````
## . ⚠️ Error Messages / Stack Traces

Verbose error messages can reveal:

- Database connection strings
    
- Credentials
    
- Internal paths
    
- Third-party keys
    

---

## . 🔍 Hidden / System Files

Misconfigured or uploaded system files may expose internal data.

- `.DS_Store`, `Thumbs.db`
    
- `index.php~`
    
- `.idea`, `.vscode`, `.editorconfig`
    

---
````

## 🛠 Recommended Tools

| Tool           | Purpose                              |
| -------------- | ------------------------------------ |
| `SecretFinder` | Extract secrets from JS files        |
| `LinkFinder`   | Extract JS endpoints                 |
| `gf`           | Grep patterns (e.g., `gf secrets`)   |
| `truffleHog`   | Find secrets in Git repositories     |
| `gitleaks`     | Scan Git repos for hardcoded secrets |
| `git-dumper`   | Dump exposed `.git/` folders         |
| `waybackurls`  | Collect historical URLs              |
| `gau`          | Fetch URLs from various sources      |
| `subjs`        | Get JavaScript files from subdomains |

---

## 🔎 Pro Tips

- Use regex tools to grep secrets:
    
    ```bash
    grep -rniE 'api[_-]?key|secret|token|authorization' .
    ```
    
- Enumerate backup and hidden files using:
    
    - `dirsearch`, `ffuf`, `gobuster`
        
- Analyze JS with:
    
    - `jsbeautifier`, `Burp Decoder`, or browser devtools
        

---

Happy Hunting! 🏹










