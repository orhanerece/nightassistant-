# NightAssistant


TUBITAK National Observatory (TUG), T100 telescope main control software



TABS DETAILING:



- **Observation Info**
  
  In this tab, one can move the telescope to the coordinates, create directories in specified path, check the field and visibility of given coordinates. Instant observability of the given coordinates can be seen as "Yes" or "No" in Visibility column.
  
  <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/1.png" alt="focus.png" width="228">
  

    <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/View.png" alt="" width="228">   
    <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/Plot.png" alt="" width="270">

        *Image of Observation Info tab (left), Image of SkyMap Button (center) and ObsChart Button (right)*

- **Focus**
  
  In this tab, there is optimized focus model on the left depends on altitude. One may adjust the focus value using "Adjust" button after selecting a value from the list. "JOG" buttons and "Go To Focus" button can also be used to control focus. Besides, on the bottom left, if autofocus checkbox is checked, focus is optimized automatically during the observation. Also live ASC image and current meteo values can be seen on the right bottom. 

  <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/2.png" alt="focus.png" width="228">

- **XCCD**
  
  
  
  Easy calculation of pixel based pointing offset.
  
  <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/3.png" alt="xccd.png" width="228">
  
  



- **Meteo**
  
  
  
  Live meteo values are displaying on this tab. RTT150 and T60 telescope meteo connection are optional while default meteo connection is T100. 
  
  <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/4.png" alt="meteo.png" width="228">
  
    
  



- **Solar System**
  
  
  
  In this tab, one can search instant positional and physical ephemerides of all known solar system objects. If object is observable at the time informations generated then GoTo button shows up to slew telescope to the object. Besides, SkyMap button brings the sky image of the coordinate and red line indicates the object's moving direction as well as amount of displacement in one hour while ObsChart brings visibility chart of the coordinate. 
  
  <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/5.png" alt="meteo.png" width="228">
  <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/2059.png" alt="2059.png" width="228">
  <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/Plot.png" alt="" width="270">
  
   *Image of Solar System tab (left), Image of SkyMap Button (center) and ObsChart Button (right)*

- **Night Report**
  
  This is a powerful tool which calculates nightly statistics of the observation and sends required informations to report database.
  
  <img title="" src="https://github.com/orhanerece/nightassistant-/blob/main/img/6.png" alt="nightreport.png" width="228">
  
***Due to corporate concerns, source codes are not public. Please, contact orhan.erece@tubitak.gov.tr for more technical informations.***
