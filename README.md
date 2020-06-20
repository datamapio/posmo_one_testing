# POSMO ONE Alpha Testing

## Help improve Posmo One with Posmo Segments
Posmo Segments can be found in the App Store and Google Play Store.            
            
We offer way more transport modes in Posmo Segments, so if you want to improve Posmo One and/or add transport modes that aren't available yet by default (e.g. Subway), we advise to record specific segments with Posmo Segments. Be however very precise with the start and stop of this particular segment.             
                 
You can then reprocess a specific day with your recorded Posmo Segments and they will be considered as ground truth and inserted into your day. We are currently working on this new feature for https://posmo.datamap.io and will let you know as soon as it is available.            
You can however already now record your Posmo Segments while using Posmo One. Once you save them, you'll can access them also at https://posmo.datamap.io.


## For your test reports  
Use [issues](https://github.com/datamapio/posmo_one_testing/issues) to publish your test reports.


### 1. Always mention the city, country and operation system (iOS/Android)
- a. Mention the city/town/municipality and country, so that we will better understand your local context.    
- b. Mention if you have an iPhone or an Android phone
- c. Mention email, day when problem occured so we can reproduce same issue in testing env. 

### 2. Always mention your settings

1 = on / 0 = off

geofence = 1 or 0            
do_not_track = 1 or 0          
wifi_over_gps = 1 or 0           
data_over_wifi_only = 1 or 0          

<img src="https://github.com/datamapio/posmo_one_testing/blob/master/posmo_one_278_settings.jpg" width="300" />

**Example:**       
geofence: 1        
do_not_track: 0           
wifi_over_gps: 0           
data_over_wifi_only: 1             
            
### 3. If something is off, follow this order of reasoning 
A. Do we have all places (static) and all segments (moving)? Do we have too many segments?        
B. Do all segments and places start at the right time?        
C. Are all places and segments classified correctly?      
            
Example report:            
"Problem A: I am missing a place on day 2020-06-20 from 14:30-15:20. Right now the walking segment extends till 15:20."       

### 4. Upload images to specify your problem
You can either send screenshots of your phone or of the web version (https://posmo.datamap.io).           
Pictures normally help to better understand the problem.
