* TODO [2015-01-03 Sat] progany-tpc: Background updating (through threads or forked process)

  So progress can still be updated even though the main process is waiting on I/O
  or external process. But we need to think of a good way to synchronize output.
* TODO [2015-01-03 Sat] progany-tpc: Animations

  Animations, like rotating line (C<- / | \ ->) or pulsating (C<. o O o .>). Also
  animation by varying colors.
* TODO [2015-01-03 Sat] progany-tpc: Detect connection speed and degrade to lower-frequency updating if connection is slow.
* TODO [2015-01-03 Sat] progany-tpc: Styles

  Preset formats as well as some behaviors like animation.
* TODO [2015-01-03 Sat] progany-tpc: Detection of column change.

  On each update(), retrieve terminal width again.
* IDEA [#B] [2014-04-29 Sel] progany-tpc: support multiline?
