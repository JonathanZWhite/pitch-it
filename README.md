Pitch-It
===================

## Get Started

### FE

- `cd pitch-it`
- 'npm -g install grunt-cli karma bower'
- 'npm install'
- 'bower install'
- `grunt serve`

To get ready for production, use grunt compile (will minify everything)

## Additional notes
- The server which listens to http://0.0.0.0:9001 can be modified inside the 'Gruntfile.js'. 
- In order to install new Angular modules:
  1. bower install [name of dependency] —save-dev
  2. bower update
  3. update build.config.json with latest dependency to compile 

