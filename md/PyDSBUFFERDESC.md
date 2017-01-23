# PyDSBUFFERDESC


## PyDSBUFFERDESC Object

A Python object, representing a DSBUFFERDESC structure

#### Properties

  - integer dwFlags

    Identifies the capabilities to include when creating a new DirectSoundBuffer object\. Specify one or more of the following:

   

       Flag

   

   

       Description

   

DSBCAPS\_PRIMARYBUFFERIndicates that the buffer is a primary sound buffer\. If this value is not specified, a secondary sound buffer will be created\.

DSBCAPS\_STATICIndicates that the buffer will be used for static sound data\. Typically, these buffers are loaded once and played many times\. These buffers are candidates for hardware memory\.

DSBCAPS\_LOCHARDWAREThe buffer is in hardware memory and uses hardware mixing\.

DSBCAPS\_LOCSOFTWAREThe buffer is in software memory and uses software mixing\.

DSBCAPS\_CTRL3DThe buffer is either a primary buffer or a secondary buffer that uses 3-D control\. To create a primary buffer, the dwFlags member of the DSBUFFERDESC structure should include the DSBCAPS\_PRIMARYBUFFER flag\.

DSBCAPS\_CTRLFREQUENCYThe buffer must have frequency control capability\.

DSBCAPS\_CTRLPANThe buffer must have pan control capability\.

DSBCAPS\_CTRLVOLUMEThe buffer must have volume control capability\.

DSBCAPS\_CTRLPOSITIONNOTIFYThe buffer must have control position notify capability\.

DSBCAPS\_STICKYFOCUSChanges the focus behavior of the sound buffer\. This flag can be specified in an IDirectSound::CreateSoundBuffer call\. With this flag set, an application using DirectSound can continue to play its sticky focus buffers if the user switches to another application not using DirectSound\. In this situation, the application's normal buffers are muted, but the sticky focus buffers are still audible\. This is useful for nongame applications, such as movie playback \(DirectShow&\#153\), when the user wants to hear the soundtrack while typing in Microsoft Word or Microsoft&\#174 Excel, for example\. However, if the user switches to another DirectSound application, all sound buffers, both normal and sticky focus, in the previous application are muted\.

DSBCAPS\_GLOBALFOCUSThe buffer is a global sound buffer\. With this flag set, an application using DirectSound can continue to play its buffers if the user switches focus to another application, even if the new application uses DirectSound\. The one exception is if you switch focus to a DirectSound application that uses the DSSCL\_EXCLUSIVE or DSSCL\_WRITEPRIMARY flag for its cooperative level\. In this case, the global sounds from other applications will not be audible\.

DSBCAPS\_GETCURRENTPOSITION2Indicates that IDirectSoundBuffer::GetCurrentPosition should use the new behavior of the play cursor\. In DirectSound in DirectX 1, the play cursor was significantly ahead of the actual playing sound on emulated sound cards; it was directly behind the write cursor\. Now, if the DSBCAPS\_GETCURRENTPOSITION2 flag is specified, the application can get a more accurate play position\. If this flag is not specified, the old behavior is preserved for compatibility\. Note that this flag affects only emulated sound cards; if a DirectSound driver is present, the play cursor is accurate for DirectSound in all versions of DirectX\.

DSBCAPS\_MUTE3DATMAXDISTANCEThe sound is reduced to silence at the maximum distance\. The buffer will stop playing when the maximum distance is exceeded, so that processor time is not wasted\.

  - integer dwBufferBytes

    Size of the new buffer, in bytes\. This value must be 0 when creating primary buffers\. For secondary buffers, the minimum and maximum sizes allowed are specified by DSBSIZE\_MIN and DSBSIZE\_MAX\.

  - WAVEFORMATEX lpwfxFormat

    Structure specifying the waveform format for the buffer\. This value must be None for primary buffers\. The application can use IDirectSoundBuffer::SetFormat to set the format of the primary buffer\. 

Sentinel