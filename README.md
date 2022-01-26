# ajql.link

My own URL shortener, deployed from @casidoo/cass.run https://github.com/cassidoo/cass.run

# Usage
After fetching, make sure NPM is set up correctly with `npm install netlify-shortener` 

To add a new url run `npm run shorten https://new-url-to-add.example.com/ shorturl` 

This will add ajql.link/shorturl to the _redirects file and will add, committ, push the changes to this repo. Netlify will then build the site and the redirect will be live within seconds. So cool!

See @kentcdodds/netlify-shortener https://github.com/kentcdodds/netlify-shortener for more info
