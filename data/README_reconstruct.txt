These files are split zip volumes created with 7-Zip.

To reconstruct on Windows:
  copy /b daily_social_media_data.zip.001 + daily_social_media_data.zip.002 + ... daily_social_media_data.zip
  7z x daily_social_media_data.zip

To reconstruct on macOS/Linux (if parts are named .001, .002, ...):
  cat daily_social_media_data.zip.* > daily_social_media_data.zip
  unzip daily_social_media_data.zip