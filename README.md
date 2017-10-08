# mYTDL
A minimalistic YouTube Video downloader powered by nodeJS. 

## Download
A compiled portable .exe can be found [here](https://github.com/dasGoogle/mYTDL/releases/latest).

## FAQ
1. Why can't I download videos in higher resolution than 720p? 
  This is caused by the technology used by YouTube for streaming the videos. Higher resolutions would require converting the downloaded files into aplayable format which would impact both performance and compatibility of the app. 
2. Where are the downloaded videos stored and can I change that directory
  Downloaded videos are stored on your Desktop. This folder cannot be changed by the user but it is specified in the download routine in the `index.html` file. 
 
## For Developers
### Download dependencies
The dependencies need to be downloaded both in the `/` folder and the `/app` folder. 
1. Project dependencies
  From the root folder run
  
   `npm install`
  
2. Application dependencies

   Change to the app directory by typing

   `cd /app`

   and install the dependencies by running

   `npm install`

### Build yourself

From the root directory of the repository, the app can be run in development mode using

`npm run start`

To build the application for a windows environment, run

`npm run dist-win`

Make sure you are running the latest version of `npm` as `npx` is required for this operation to work. 
