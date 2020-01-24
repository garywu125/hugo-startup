deploy netlify:
 - before git:
   add file : netlify.toml (**update hugo version**)
   update config.toml :
   baseURL = "https://gy-hugo101.netlify.com/"
 - git sync:  

 - github netlify application setting: allow netlify to access the repository
   https://github.com/settings/profile->application->netlify->config buttom

 - go to netlify.com :
   - https://app.netlify.com/teams/garywu125/sites
   - deploy new site from git : press new site from git
   - rename site name 
 