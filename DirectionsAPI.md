# WebGIS
# Directions API
# URL
https://maps.googleapis.com/maps/api/directions/json?origin=McMasterUniversity&destination=McMater+University+1280+Main+St+W,+Hamilton,+ON+L8S+4L8&key=AIzaSyA5a1FoKmbmQ1djPh6pRx7oiknBf3ACNOE

# JSON Return
```
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJwSr3RKyELIgRHAFDYeoAnjk",
         "types" : [ "establishment", "point_of_interest", "university" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJwSr3RKyELIgRHAFDYeoAnjk",
         "types" : [ "establishment", "point_of_interest", "university" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.2615895,
               "lng" : -79.9233553
            },
            "southwest" : {
               "lat" : 43.2615895,
               "lng" : -79.9233553
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "1 m",
                  "value" : 0
               },
               "duration" : {
                  "text" : "1 min",
                  "value" : 0
               },
               "end_address" : "1280 Main St W, Hamilton, ON L8S 4L8, Canada",
               "end_location" : {
                  "lat" : 43.2615895,
                  "lng" : -79.9233553
               },
               "start_address" : "1280 Main St W, Hamilton, ON L8S 4L8, Canada",
               "start_location" : {
                  "lat" : 43.2615895,
                  "lng" : -79.9233553
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "1 m",
                        "value" : 0
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 0
                     },
                     "end_location" : {
                        "lat" : 43.2615895,
                        "lng" : -79.9233553
                     },
                     "html_instructions" : "Head",
                     "polyline" : {
                        "points" : "}o`gG~_yfN"
                     },
                     "start_location" : {
                        "lat" : 43.2615895,
                        "lng" : -79.9233553
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "}o`gG~_yfN"
         },
         "summary" : "",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
