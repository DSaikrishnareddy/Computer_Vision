<h1> Computer_Vision </h1>

<h2> Max, Min, Midpoint and Alpha-Trimmed Mean Filters </h2>

<h3> Max and Min Filters </h3>
  The median filter is by far the order-statistic filter most used in image processing, it is by no means the only one. The median represents the 50th percentile of a ranked set of numbers, but you will recall from basic statistics that ranking lends itself to many other possibilities. For example, using the 100th percentile results in the so-called max filter.

   <h4> MAX Filter </h4>
        This filter is useful for finding the brightest points in an image or for eroding dark regions adjacent to bright areas. Also, because pepper noise has very low values, it   is reduced by this filter as a result of the max selection process in the subimage area Sxy.Max filter is good for pepper noise
        
<img src="https://github.com/DSaikrishnareddy/Computer_Vision/blob/main/Max_filter.PNG" align="center">
  
  <h4> MIN Filter </h4>
        The 0th percentile filter is the Min filter which is useful for finding the darkest points in an image or for eroding light regions adjacent to dark areas. Also, it reduces  salt noise as a result of the min operation. Min filter is good for salt noise
        
<img src="https://github.com/DSaikrishnareddy/Computer_Vision/blob/main/Min_filter.PNG" >

<h3> Mid Point Filter </h3>
   Good for random Gaussian and uniform noise.

<img src="https://github.com/DSaikrishnareddy/Computer_Vision/blob/main/MidPoint_filter.PNG" >

<h3> Alpha-Trimmed Mean Filter </h3>

   If we delete the d/2 lowest and the d/2 highest intensity values of g(r, c) in the neighborhood the value of d can range from 0 to mn-1 When d=0 the alpha-trimmed.
   
<img src="https://github.com/DSaikrishnareddy/Computer_Vision/blob/main/Alpha_Trimmed_filter.PNG" >
  

