** How to add a file type **

The functions you have to add things to are:
- findMeta.madeBy
- findMeta.allSeshMeta
- generalFunctions.stripTags

The attributes that allSeshMeta wants to assign:
- allMeta['startMom'] - a datetime of the session start time
- allMeta['Name'] - Session name, not sure
- allMeta['FileSessionN'] - where the Session is found in the Xfold's session list?
- allMeta['TStep'] - a timedelta of the time between images
- allMeta['Chan'] - a list of the channel names in the Session
- allMeta['NC'] - the number of channels
- allMeta['NT'] - the number of time points
- allMeta['NZ'] - the number of z-slices
- allMeta['ZStep'] the distance in um between z-slices
- allMeta['NF'] - the number of fields
- allMeta['NM'] - the number of montage tiles
- allMeta['NY'] - the number of pixels in Y
- allMeta['NX'] - the number of pixels in X
- allMeta['NMX'] - the number of tiles in the x-direction
- allMeta['NMY'] - the number of tiles in the y-direction
- allMeta['MOlap'] - the percentage overlap of montage tiles
- allMeta['FieldNMYs'] - a list of NMY for each field in case it changes?
- allMeta['FieldNMXs'] - a list of NMX for each field in case it changes?
- allMeta['MontageOrder'] - e.g. "LDUR" or "TilePos"
- allMeta['SessionN'] - apparently only used for multisesh files