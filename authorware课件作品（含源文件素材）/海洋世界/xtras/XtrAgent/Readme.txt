XtrAgent Trial Version 2.0
--------------------------

Developed by Tomer Berda, DirectXtras Inc.
Copyright 1998-99. 
Last updated: 10 May 1999.

This is a trial version of XtrAgent. You can use it to see if it 
provides you with the features you are looking for. 
The trial version does not operate under projectors, packages 
and Shockwave. In addition, the 'File' member/icon property
and the ability to create new XtrAgent members/icons on the fly
are not available in this trial version.

You have to license the Xtra to obtain the disabled features,
run-time capability, and the license to use and freely distribute
XtrAgent along with your applications.


Product Information
-------------------
XtrAgent is an Asset Xtra which enables the use of Microsoft's revolutionary 
"Agent" technology in Director, Authorware and Shockwave applications, that 
provides a foundation for more natural ways for people to communicate with 
their computers. 

XtrAgent adds a new type of member to your cast - Agent.
Agent is an interactive animated character that can be drawn on top 
of all other sprites and windows and even outside of the stage area. 
It can speak, via a text-to-speech engine or recorded audio, and accept 
spoken voice commands.

Agents can be used as guides, coaches, entertainers, or other types of 
assistants or specialists. 

Using XtrAgent, developers can utilize Text-To-Speech & Speech Recognition 
engines and freely distribute them with their applications!
In addition, XtrAgent provides powerful animation capability and interactivity, 
with support for high-quality lip-synching at an incredible ease of development. 
It comes with ready-to-use characters and also support custom characters that 
developers can create using the Microsoft Agent character editor.

XtrAgent is available for Windows 9X & NT. It is possible to use it along with 
the MacOS version of Xpress Xtra to have a cross-platform Text-To-Speech solution.


System requirements
-------------------

- Microsoft Windows® 95, Windows 98, Windows NT® 4.0 (x86) or later 
- Internet Explorer version 3.02 or later 
- Personal computer with a Pentium 100 MHz or higher processor 
- At least 16 MB of memory
- Microsoft Agent core components 2.0 or later
- Hard-disk space for core components: 1 MB
- Text-To-Speech and Speech recognition engines (recommended)
- Windows compatible sound card (recommended)
- Compatible speakers and microphone (recommended)
- Microsoft Mouse or compatible pointing device (recommended)
- Hard-disk space for optional components: 
  Lernout & Hauspie TruVoice® Text-to-Speech engine for speech output: 1.6 MB 
  Microsoft Speech Recognition Engine for speech input: 22 MB 
  Characters installed locally: 2-4 MB per character 


Explanation of licensing-availability:
--------------------------------------

XtrAgent is a commercial product. 
You can license it from http://www.directxtras.com for 
$399 per developer, one-time licensing fee.

Along with the Xtra, you will receive full documentation, sample 
codes and direct support by e-mail.

The licensed product includes a runtime version of the Xtra 
that can be freely distributed along with your applications. 

Auto-downloadable Shockwave safe version can be licensed seperately.


History
-------

May 10, 1999;
Version 2.0 released.

- The Xtra is now compatible with Authorware and Shockwave. 
- Auto-downloadable Director Shockwave safe version is available.

- New Sprite functions: Think, Listen, Activate, ShowPopupMenu, GestureAt, Interrupt
- New Member/Icon properties: PopupMenu, TTSModeID, SRModeID, SRStatus
- New Member/Icon functions: ShowDefaultCharacterProperties
- New Events: VisibleState, ActivateInputState, Move, ActiveClientChange, 
  DefaultCharacterChange, ListeningState

- The new version requires Microsoft Agent core components 2.0 or later.

- Creating a new Member/Icon without specifying a filename loads the default 
  character (if available). If XtrAgent cannot find a linked character file using 
  Director/Authorware standard filename resolution algorithm, it searches the 
  Agent's characters directory for it. 
  See the File Member/Icon property for more info and changes.

- StopAll() can now stop only Show requests.

- SREngine Member/Icon property was removed. Use SRModeID instead.

- 'Suspended' Member/Icon property was removed. Microsoft Agent 2.0 or later
  cannot be in a suspended mode anymore.

- Restart and ShutDown events were removed, Microsoft Agent 2.0 or later
  cannot be shutdown or restarted anymore.

- Multiple cast Members/Icons for the same character are supported for Authoring
  convenience purposes, though you still can't display the same character more 
  than once on the screen.

April 18, 1999;
Version 1.0.1 released.

- VisibleState event was added.
- Fixed crash that sometimes occured with Microsoft Agent 2.0 under Director 7, 
  when you quit the application with visible Agent character(s) that has some 
  uncompleted requests.
- Fixed some other minor issues related to Microsoft Agent 2.0 and Director 7.

June 1, 1998; 
Version 1.0 released.

- XtrAgent built-in error messages replaced with error codes that can be handled 
  from lingo. See the sample movie for code that checks whether the character files 
  were loaded properly, if there is a compatible speech recognition engine 
  installed, and whether Microsoft Agent is installed and working properly.

- Speech output tags and animations for Genie, Robby and Merlin are now documented.

- New XtrAgent Member/Icon Properties: SREngine, SRHotKey

- New XtrAgent Sprite Event: Bookmark

- New XtrAgent Sprite Function : Stop

Bugs found & fixed:
- ExtraData property returned the Description property and was corrected.

May 18, 1998;
- Version 1.0 beta/preview released.


                             DirectXtras Inc.

               P.O Box 423417 San Francisco, CA 94142-3417
               Voice: +1-415-505-8249, Fax: +1-650-9384633
             E-mail General information: info@directxtras.com
              E-mail Technical Support: supp@directxtras.com
 
-----------------------------------------------------------------------------

       Please send comments, suggestions and bug reports to :
                     supp@directxtras.com
	

Further information on Microsoft Agent technology can be found at 
http://msdn.microsoft.com/workshop/imedia/agent/default.asp and in 
the XtrAgent HomePage located at http://www.directxtras.com/

Xtra is a trademark of Macromedia, Inc.
