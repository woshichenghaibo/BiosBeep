# BiosBeep
VB Beep sound from chipset
Const D1 = 264
Const R2 = 297
Const M3 = 330
Const F4 = 352
Const S5 = 396
Const L6 = 440
Const T7 = 495
Const D8 = 528
Private Declare Function Beep Lib "kernel32" (ByVal dwFreq As Long, ByVal dwDuration As Long) As Long
Private Sub Command1_Click()
Beep R2, 1000
Beep F4, 700
Beep L6, 600
Beep M5, 1700
Beep F4, 800
Beep S3, 1000
Beep R2, 600
End Sub


