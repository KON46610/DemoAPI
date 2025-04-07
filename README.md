Created a SpringBoot web application
Created three GET calls
/one returns ‘this is one’
/two returns ‘this is two’
/three returns ‘this is three’
Only two of these three calls respond when called concurrently.  The third one returns an appropriate http return code
Default SpringBoot webcalls is not affected by 2 thread limitation i.e., calls under /actuator like /info or /health respond.
Unit Tests are included
