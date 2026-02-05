# SingleA_Armageddon_VersionD
collection of code files for troubleshooting exercise and practice. Time to git ghud, padawans.
First error fixed was for the Index4.html file. Discovered a syntax error on Line 91. This error was missing the (}) before the word else. Upated line 91 to include the needed (})
line 32 removed the equal sign (=) from behind the Less than sign (<)
Line 42 and 43 changed Math.min.apply to Math.max.apply and Math.max.apply to Math.min.apply 
Line 82 An error of the Property names don’t match what callers expect. The code expected stats.highest and stats.lowest, but this function returns max and min. Also the min and max are reversed as max: Math.min(...) and min: Math.max(...). I kept the caller unchanged and fix the function to return the right names with the right values. The script now shows as highest: Math.max.apply(null, arr), and lowest: Math.min.apply(null, arr). When they don’t line up, it flags a logic issue even though the code is valid.
Line 106 A logic error: increments instead of decrements script was shown as index++, but needed to be index-- to close the loop. 