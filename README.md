# msg_box

### Create message box easily in Python
This module uses `ctypes` to create easy-to-use message boxes.

#### Installation

    pip install msg_box
   

#### Example
  
    import msg_box as mb
    
    agreement = mb.agreement('Agreement', 'Are you agree?', is_cancel = True)
    if agreement == None:
        mb.alert('Sorry to bother!', 'Exiting.')
        exit()
    elif agreement:
        mb.alert('Thanks!', 'Have a great day.')
    else:
        mb.alert('Oooh', 'Sorry', icon = 'stop')



This is my first module ever! 

