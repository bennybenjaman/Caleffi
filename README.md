# <ins>Instructions</ins>

### <ins>Create a file and insert some lines then save it as a .dat</ins>

`nano testfile.dat `

### <ins>Encode the file</ins>

`./encode encoded.wav 8000 16 1 encoded-testfile.dat`

**Transmission should have a 4 bar space in between each datagram.**

### <ins>Decode the file</ins>

`./decode decoded.dat recorded.wav`
