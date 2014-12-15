# IfInString (Command)/ InStr (function)

Documentation: <http://ahkscript.org/docs/commands/IfInString.htm>

## InStr Examples

### Example 1

For example, the position of "abc" in "123abc789" is always 4. 
Specify 2 for Occurrence to return the position of the second match, 3 for the third match, etc.

   ```autohotkey
haystack:="123abc789abc"
pos1:=InStr(haystack,"abc")     ; 1st occurence position 4
pos2:=InStr(haystack,"abc",,,2) ; 2nd occurence position 10
MsgBox % pos1 "`n" pos2         ; Shows 4 & 10
   ```

### Example 2

etc.
