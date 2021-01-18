# Vehicle-class-analysis

#### ATTRIBUTE INFORMATION
<b>compactness</b> - float,average perimeter**2/area<br>
<b>circularity</b> - float,average radius**2/area<br>
<b>distance_circularity</b> - float,area/(av.distance from border)**2<br>
<b>radius_ratio</b> - float,(max.rad-min.rad)/av.radius<br>
<b>pr_axis_aspect_ratio</b> - float,(minor axis)/(major axis)<br>
<b>max_length_aspect_ratio</b> - float,(length perp. max length)/(max length)<br>
<b>scatter_ratio</b> - float,(inertia about minor axis)/(inertia about major axis)<br>
<b>elongatedness</b> - float,area/(shrink width)**2<br>
<b>pr_axis_rectangularity</b> - float,area/(pr.axis length*pr.axis width)<br>
<b>max_length_rectangularity</b> - float,area/(max.length*length perp. to this)<br>
<b>scaled_variance_major_axis</b> - float,(2nd order moment about minor axis)/area<br>
<b>scaled_variance_minor_axis</b> - float,(2nd order moment about major axis)/area<br>
<b>scaled_radius_gyration</b> - float,(mavar+mivar)/area<br>
<b>skewness_major_axis</b> - float,(3rd order moment about major axis)/sigma_min**3<br>
<b>skewness_minor_axis</b> - float,(3rd order moment about minor axis)/sigma_maj**3<br>
<b>kurtosis_minor_axis</b> - float,(4th order moment about major axis)/sigma_min**4<br>
<b>kurtosis_major_axis</b> - float,(4th order moment about minor axis)/sigma_maj**4<br>
<b>hollows_ratio</b> - float,(area of hollows)/(area of bounding polygon)<br>
<b>vehicle_class</b> - string,"Predictor Class. Values: Opel, Saab, Bus, Van"<br>
