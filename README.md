# appGuard

Application are constantly created and destroyed in kubernetes. 
This is an operator check, monitor and ensure core applications are constantly up and running. 
It sends alerts to aplication insights, other logging or email to alert users

Internals of apps or pods such as when certificates are updated, what is the dns routing that is happening in the k8s cluster - sometimes these network dns resolution is intermitent and does not follow the same ip routing path. 

How do you know your pod is working 
