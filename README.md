# cli
CLAIMED CLI - all components available via cli at your fingertips

## installation
sudo curl -o /usr/bin/claimed https://raw.githubusercontent.com/claimed-framework/cli/main/claimed  
sudo chmod 755 /usr/bin/claimed

## example usage
claimed claimed-util-cos:0.3 access_key_id=xxx secret_access_key=yyy endpoint=https://s3.us-east.cloud-object-storage.appdomain.cloud bucket_name=era5-cropscape-zarr path=/ recursive=True operation=ls
