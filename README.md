# enough-
otKeySet("{ESC}", "_Exit")  While 1    For $iCount = 0 To 5       ; Current value       ConsoleWrite($iCount &amp; @CRLF)            ; Just to keep it slow enough to read       Sleep(500)    Next WEnd  Func _Exit()     Exit EndFunc
