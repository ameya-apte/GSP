1. GIT TEST
	#GSP
	#GSP1
	#GSP2
2. https://opensource.com/article/18/1/step-step-guide-git

3. Why does dual booting with ubuntu change my date and time in windows?

Answer for this is very trivial 

TWO important things to remember ubuntu assumes the system setup time (which can be set by going into setup during boot of a laptop i.e by pressing some function key eg f5) as GMT whereas windows assumes the system time as that which we set in windows eg GMT+5 30(for delhi or kolkata india).

hence if we set the time in ubuntu as GMT +5 30(eg 11 30 am) then as ubuntu assumes the system time as GMT the system time becomes (11 30 minus 5 30 i.e 6 00 am) and hence as windows assumes the time same as system time windows time becomes 6 00 am.

hence to overcome this what we simply need to do is set the system time to current required time i.e 11 30 am hence the windows time becomes 11 30 am
but due to this the ubuntu time becomes 11 30 plus 5 30  i.e 5 pm as ubuntu assumes system time as GMT hence to correct this now we just need to select time zone as GMT +00 00 i.e LONDON UK so that it takes the system time directly without adding anything and hence the ubuntu time is GMT i.e 
11 30 am and the windows time is equal to the setup time i.e 11 30 am


i.e windows assumes the setup time as GMT +5 30 as we have set timezone as kolkata in windows but ubuntu always assumes setup time as GMT even if we set timezone as GMT +5 30 kolkata in ubuntu hence if we set a timezone in ubuntu it varies the GMT of setup accordingly i.e if we set 12 30 am(and timezone as GMT + 2 00  in ubuntu) what ubuntu does is it sets the GMT accordingly i.e 12 30 minus 2 00 i.e 10 30 am hence setup time now becomes 10 30 am according to timezone we select in ubuntu hence if we set the timezone as 12 30 am (GMT + 00 00 in ubuntu) then the ubuntu sets the GMT as  
12 30 minus 00 00 i.e 12 30 am hence setp time now becomes 12 30 am.
  





