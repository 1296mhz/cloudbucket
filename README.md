### CloudBucket
#### by Sahat Yalkabov and Emily Boden
CloudBucket allows you to upload various files and it then tags it automatically based on the filetype. 
For instance music files will be automatically tagged with lyrics, keywords, similar artists, album cover.
Text documents, on the other hand, will have different tags associated with each file - keywords, entities, concepts.
Videos and photos are tagged as well using other techniques.

*Insert screenshot here*

### Features
- 1GB of free storage
- Cross-platform - works on iOS, Android and Desktop
- Semantic search
- Face recognition
- Text content analysis

### Dependencies

#### Frontend
- jQuery
- Bootstrap
- Magnific Popup
- Ladda
- Vex.js
- iScroll
- Entypo Icons
- iDangero.us Swiper
- animate.css
- jquery-easy-pie-chart
- swipe.js
- jquery.tagsinput
- humane.js
- fastclick.js
- jquery.knob
- jquery.raty
- jquery.transit
- hammer.js
- Grunt.js
- Bower

#### Backend
- Node.js
- Python 2.7
- Express.js
- async
- AWS SDK
- connect-flash
- connect-mongo
- Case
- email.js
- epub-parser
- filesize
- fluent-ffmpeg
- Dropbox
- musicmetadata
- Mongoose
- passport
- request
- restler
- underscore
- underscore.string

#### API Services
- Google OAuth 2.0
- Last.fm
- Musixmatch
- Google Books API
- Alchemy API
- SkyBiometry

### Downloading
Clone the repository using Git:
```
git@github.com:sahat/cloudbucket.git
```

### Running Locally
The only requirements are **Node.js** >= 0.10 and **Python** 2.7. Locate the directory that you
just cloned and then run:
```
npm install package.json
node app.js
```
MongoDB and Amazon S3 configuration is already pre-configured to use production servers. 
