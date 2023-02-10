  # Permissions
    4 >> Read only >>r
    2 >> Write only >>w
    1 >> Execute only >>x
    0 >> None >>---
    
    4 + 2 + 1 = 7 >> rwx
    4 + 2 = 6 >> rw
    4 + 1 = 5 >> rx
    2 + 1 = 3 >> wx
    0 >> ---
    
    chmod 750 filename
    chmod -R 750 foldername
