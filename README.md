# read_tek_osc
An example to read tektronix MDO3000 series oscilloscope data directly into the PC using pyVisa 1.9 
The addition of the new query_binary_values function allows the reading to be done in one line

The current implementation reads the analog channels. It requires the user to first set the number of channels to read
