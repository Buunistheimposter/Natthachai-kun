SEND"please enter temperature"TO DISPLAY
RECEIVE tems FROM DISPLAY
IF tems < 18 degrees THEN
SEND"Cold,the perfect temparature for sleep is 18-21 degrees"TO DISPLAY
ELSE
IF tems > 21 degrees THEN
SEND"Perfect"TO DISPLAY
ELSE
SEND"No!, the perfect temperature for sleep is 18-21 degrees"TO DISPLAY
END IF
END IF
