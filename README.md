# Sublime promoter

This is for those of you who are fully aware that the editor they use to work in is in fact another browser. Visual Code is such a calamity - a resource-hungry myopic creature resulted from an unorthodox scientific experiment - that even Frankenstein would fear. 

Sublime Text is a native sophisticated text editor for code, markup and prose. You'll love the slick user interface, and extraordinary features. When your workstation needs all the power and resources available for heavy compilation and background processing, another chrome opened (that identifies as a text editor) is a nightmare (that is if you use chrome - another monster).
Sublime is free for personal use. That is why the following is just for educational purposes only:

The following is for the Sublime v4

```bash
00007FF6AFC4B63D | C3                  | ret                                                  |
00007FF6AFC4B63E | C601 00             | mov byte ptr ds:[rcx],0                              |
00007FF6AFC4B641 | C3                  | ret                                                  |
to
00007FF6AFC4B63D | C3                  | ret                                                  |
00007FF6AFC4B63E | C601 01             | mov byte ptr ds:[rcx],1                              | <-
00007FF6AFC4B641 | C3                  | ret                                                  |


# ---------------------------------------------------------------------------------------------
00007FF6AFCE7504 | 7F 51               | jg sublime_text.7FF6AFCE7557                         |
00007FF6AFCE7506 | 31C0                | xor eax,eax                                          |
00007FF6AFCE7508 | 8805 AA3A8200       | mov byte ptr ds:[7FF6B050AFB8],al                    |
to
00007FF6AFCE7504 | 7F 51               | jg sublime_text.7FF6AFCE7557                         |
00007FF6AFCE7506 | B0 01               | mov al,1                                             |
00007FF6AFCE7508 | 8805 AA3A8200       | mov byte ptr ds:[7FF6B050AFB8],al                    |
``` 

This material is for educational and research purposes only. All the information on this page are meant for developing a critical attitude among the users and help preventing the - I don't care if it works - mindeset. We insists that this information shall not be used for causing any kind of damage directly or indirectly and a license be bought.