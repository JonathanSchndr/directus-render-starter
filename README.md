# Directus Render Starter

Host Directus on render.com

1. Use this repo as template to create your own
2. Create render.com account
3. Login render.com and create a Web Service and PostgreSQL DB
   1. Web Service Settings:
      1. Build Command: npx directus bootstrap
      2. Start Command: npx directus start
      3. Health Check Path:  /server/health
4. Change the db connection in the .env file
5. Push your changes to the repo
6. Done!

Important:
If you want your uploads folder not to be deleted after a push, you need to save them as filestorage under render.com Web Service > Settings > Disks. Mouth Path: /opt/render/project/src/uploads
