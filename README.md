# POSMO ONE Alpha Testing

## Help improve Posmo One with Posmo Segments
[Posmo Segments](https://medium.com/@datamapio/posmo-segments-introduction-7af3183cfe6b) can be found in the [App Store](https://itunes.apple.com/us/app/posmo-segments/id1450602777) and [Google Play Store](https://play.google.com/store/apps/details?id=io.datamap.posmo_segments).            
            
We offer way more transport modes in Posmo Segments, so if you want to improve Posmo One and/or add transport modes that aren't available yet by default (e.g. Subway), we advise to record specific segments with Posmo Segments. Be however very precise with the start and stop of this particular segment.             
                 
You can then reprocess a specific day with your recorded Posmo Segments and they will be considered as ground truth and inserted into your day. We are currently working on this new feature for https://posmo.datamap.io and will let you know as soon as it is available.            
You can however already now record your Posmo Segments while using Posmo One. Once you save them, you'll can access them also at https://posmo.datamap.io.

### Posmo Segments helps to benchmark starts/stops, duration and kilometers
Using Posmo One together with Posmo Segments helps also to be precise/to benchmark, as Posmo Segments always displays start, end times as well as duration and total kilometers.
You don't need to do this for all segments, just for the ones you like and for the ones where other transport modes than:     
      
- walking
- running
- bike
- tram
- bus
- train
- car               

are used.

## For your test reports  
Use [issues](https://github.com/datamapio/posmo_one_testing/issues) to publish your test reports.

### 0. Tell us if you are fine, when we respond publicly to your questions

Being in Alpha, we looking at your data will tell us what is wrongly interpreted. The more diversity of cases we see, the better our ML will become. For now it helps to scrutinize the day and segments you point out. And do this visually most of the time. 

#### Assumption 1: 
If you help us with that, you agree that we look at your data. 

#### Assumption 2: 
- Public = shown in Issues, we respond publicly and - if that helps - with the aid of images. As long as you do not write "SEMIPRIVATE" on top of your issue, we assume that we can respond to your problem with the help of images.
- SEMIPRIVATE = we read your question on Issues and respond only briefly in text and if images are needed, we send you a mail
- Private = send us a mail (send to roger at datamap.io). 

### 1. Always mention the city, country and operation system (iOS/Android), username and day
- a. Mention the city/town/municipality and country, so that we will better understand your local context.    
- b. Mention if you have an iPhone or an Android phone
- c. Mention your username/email
- d. Mention the day when the problem occured. This helps us to reproduce the same issue in our testing environment. 

### 2. Always mention your settings

1 = on / 0 = off

geofence = 1 or 0                    
wifi_over_gps = 1 or 0           
data_over_wifi_only = 1 or 0  
do_not_track = 1 or 0          

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
