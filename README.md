# Notea
___Your Self-Hosted Notion Style Note Taking App___

> Notea is a markdown, notion-like note-taking app stored using compatible S3 storage and accessible via any modern web browser.
> Works great as a Progressive Web App (PWA) on any device, including Android, iOS and iPad.

## How to use this template

This template has pre-configured variables to use [storj.io](https://storj.io) as the S3 backend for your data. Storj is free up to 25GB, so definitely check it out. Almost any S3 backend can be used [(see here for more details)](https://github.com/notea-org/notea).  Update any preconfigured variables if needed, in addition to adding S3 credentials and a GUI password, and you are ready to go!

1. Click the **Deploy on Railway** button below
2. If not using Storj, make sure to update the pre-configured variables (filled with defaults below):
    - STORE_END_POINT=https://gateway.storjshare.io
    - STORE_REGION=us1.storj.io
3. Enter S3 bucket name and credentials, along with a password for you to access your notes:
    - STORE_BUCKET=notea-bucket-name
    - STORE_ACCESS_KEY=somelongalphanumericstringforaccesskey
    - STORE_SECRET_KEY=somelongalphanumericstringforsecretkey
    - PASSWORD=make!som3thingsecurIt@y
4. Click Deploy and wait for your notea to build and deploy
5. A URL will be auto-generated for you that can be found in a few places in your [railway.app dashboard](https://railway.app/dashboard) 
6. Enjoy having always synced, feature rich notes!


**Click below to deploy!**

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/OhFC4F?referralCode=_Fx4yk)

_Credit: [Notea Org](https://github.com/notea-org/notea)_
