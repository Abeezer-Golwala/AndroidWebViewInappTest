Includes Custom User input for user property, user id and event with event properties. Also includes webview with clevertap integration in it. 
Added below code to where the web pushes event 
if (window.CleverTap) {
  // Call Android interface             
  CleverTap.pushEvent("AbWebViewpush");          
} 
