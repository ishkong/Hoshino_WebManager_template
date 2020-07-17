# Hoshino_WebManager_template
A template for Hoshino Services Web Manager

## How to use

### HTTPS and use reverse proxy

1. Download and replace files

2. Restart Hoshino

### HTTPS but no reverse proxy

1. Download files

2. Add ':{{port}}' after ***ALL*** '{{public_address}}' in files

3. Replace files

4. Restart Hoshino

### HTTP but use reverse proxy

1. Download files

2. Replace ***ALL*** 'https' with 'http' in files

3. Replace files

4. Restart Hoshino

### HTTP and no reverse proxy

1. Download files

2. Find ***ALL*** notes and follow the notes

3. Replace files

4. Restart Hoshino

#### Possible file locations

| File Name | Line |
| :----: | :----: |
| view.py | 111 |
| base.html | 8 |
| by_group.html | 28 |
| by_service.html | 26 |
| group_services.html | 55 |
| service_groups.html | 95 |
