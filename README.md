<h1> TFRecord_Realistic_USA_RoadSigns_160classes</h1>

<h2>Slightly Realistic USA RoadSigns 160classes</h2>

This is a USA RoadSigns train and valid dataset annotated by TFRecord format. 
It contains 160 classes, and each image size is 512x512.<br>

This dataset has been created based on <a href="https://en.wikipedia.org/wiki/Road_signs_in_the_United_States">Road signs in the United States.</a>


<h2>160classes (label_map.yaml)</h2>
<pre>
1: '270_degree_loop'
2: 'Added_lane'
3: 'Added_lane_from_entering_roadway'
4: 'All_way'
5: 'Be_prepared_to_stop'
6: 'Bicycles'
7: 'Bicycles_and_pedestrians'
8: 'Bicycles_left_pedestrians_right'
9: 'Bicycle_wrong_way'
10: 'Bike_lane'
11: 'Bike_lane_slippery_when_wet'
12: 'Bump'
13: 'Bus_lane'
14: 'Center_lane'
15: 'Chevron_alignment'
16: 'Circular_intersection_warning'
17: 'Cross_roads'
18: 'Curve'
19: 'Dead_end'
20: 'Deer_crossing'
21: 'Detour'
22: 'Detour_right'
23: 'Dip'
24: 'Double_side_roads'
25: 'Do_not_drive_on_tracks'
26: 'Do_not_enter'
27: 'Do_not_pass_stopped_trains'
28: 'Emergency_signal'
29: 'End_detour'
30: 'Except_right_turn'
31: 'Fallen_rocks'
32: 'Flagger_present'
33: 'Fog_area'
34: 'Golf_cart_crossing'
35: 'Go_on_slow'
36: 'Gusty_winds_area'
37: 'Hairpin_curve'
38: 'Hazardous_material_prohibited'
39: 'Hazardous_material_route'
40: 'Hidden_driveway'
41: 'Hill_bicycle'
42: 'Horizontal_alignment_intersection'
43: 'Horse_drawn_vehicle_ahead'
44: 'Keep_left'
45: 'Keep_left_2'
46: 'Keep_right'
47: 'Keep_right_2'
48: 'Lane_ends'
49: 'Left_lane'
50: 'Left_turn_only'
51: 'Left_turn_or_straight'
52: 'Left_turn_yield_on_green'
53: 'Loading_zone'
54: 'Low_clearance'
55: 'Low_ground_clearance_railroad_crossing'
56: 'Merge'
57: 'Merging_traffic'
58: 'Metric_low_clearance'
59: 'Minimum_speed_limit_40'
60: 'Minimum_speed_limit_60km'
61: 'Narrow_bridge.jpg'
62: 'Narrow_bridge'
63: 'National_network_prohibited'
64: 'National_network_route'
65: 'Night_speed_limit_45'
66: 'Night_speed_limit_70km'
67: 'No_bicycles'
68: 'No_entre'
69: 'No_hitch_hiking'
70: 'No_horseback_riding'
71: 'No_large_trucks'
72: 'No_left_or_u_turn'
73: 'No_left_turn'
74: 'No_left_turn_across_tracks'
75: 'No_outlet'
76: 'No_parking'
77: 'No_parking_bus_stop'
78: 'No_parking_from_830am_to_530pm'
79: 'No_parking_from_830am_to_530pm_2'
80: 'No_parking_in_fire_lane'
81: 'No_parking_Loading_zone'
82: 'No_parking_on_pavement'
83: 'No_pedestrians'
84: 'No_pedestrian_crossing'
85: 'No_right_turn'
86: 'No_rollerblading'
87: 'No_standing_any_time'
88: 'No_stopping_on_pavement'
89: 'No_straight_through'
90: 'No_train_horn_warning'
91: 'No_turns'
92: 'No_unauthorized_vehicles'
93: 'No_u_turn'
94: 'Offset_roads'
95: 'One_direction'
96: 'One_way'
97: 'Parking_with_time_restrictions'
98: 'Pass_on_either_side'
99: 'Pass_road'
100: 'Path_narrows.jpg'
101: 'Path_narrows'
102: 'Pedestrian_crossing'
103: 'Railroad_crossing'
104: 'Railroad_crossing_ahead'
105: 'Railroad_intersection_warning'
106: 'Ramp_narrows'
107: 'Reserved_parking_wheelchair'
108: 'Reverse_curve'
109: 'Reverse_turn'
110: 'Right_lane'
111: 'Right_turn_only'
112: 'Right_turn_or_straight'
113: 'Road_closed'
114: 'Road_closed_ahead'
115: 'Road_narrows'
116: 'Road_slippery_when_wet'
117: 'Rough_road'
118: 'Runaway_vehicles_only'
119: 'School'
120: 'School_advance'
121: 'School_bus_stop_ahead'
122: 'School_bus_turn_ahead'
123: 'School_speed_limit_ahead'
124: 'Sharp_turn'
125: 'Side_road_at_an_acute_angle'
126: 'Side_road_at_a_perpendicular_angle'
127: 'Single_lane_shift_left'
128: 'Skewed_railroad_crossing'
129: 'Snowmobile'
130: 'Speed_limit_50'
131: 'Speed_limit_80km'
132: 'Stay_in_lane'
133: 'Steep grade'
134: 'Steep_grade_percentage'
135: 'Stop'
136: 'Stop_here_for_pedestrians'
137: 'Stop_here_for_peds'
138: 'Straight_ahead_only'
139: 'Tractor_farm_vehicle_crossing'
140: 'Tractor_farm_vehicle_crossing_2'
141: 'Truck crossing_2'
142: 'Truck_crossing'
143: 'Truck_rollover_warning'
144: 'Truck_route_sign'
145: 'Truck_speed_Limit_40'
146: 'Turning_vehicles_yield_to_pedestrians'
147: 'Turn_only_lanes'
148: 'Two_direction'
149: 'Two_way_traffic'
150: 'T_roads'
151: 'Wait_on_stop'
152: 'Weight_limit_10t'
153: 'Winding_road'
154: 'Workers_on_road'
155: 'Work_zone_for_speed_limit'
156: 'Wrong_way'
157: 'Yield'
158: 'Yield_here_to_pedestrians'
159: 'Yield_here_to_peds'
160: 'Y_roads'

</pre>

<h2>Sample train images </h2>
<table>
<tr><td>
<img src="./asset/roadsigns_1000.jpg" width="512" height="auto">
</td></tr>

<tr><td>
<img src="./asset/roadsigns_1100.jpg" width="512" height="auto">
</td></tr>
<tr><td>
<img src="./asset/roadsigns_1200.jpg" width="512" height="auto">
</td></tr>
<tr><td>
<img src="./asset/roadsigns_1300.jpg" width="512" height="auto">
</td></tr>
<tr><td>
<img src="./asset/roadsigns_1400.jpg" width="512" height="auto">
</td></tr>
<tr><td>
<img src="./asset/roadsigns_1500.jpg" width="512" height="auto">
</td></tr>
<tr><td>
<img src="./asset/roadsigns_1600.jpg" width="512" height="auto">
</td></tr>
<tr><td>
<img src="./asset/roadsigns_1700.jpg" width="512" height="auto">
</td></tr>
<tr><td>
<img src="./asset/roadsigns_1800.jpg" width="512" height="auto">
</td></tr>
<tr><td>
<img src="./asset/roadsigns_1900.jpg" width="512" height="auto">
</td></tr>

</table>



