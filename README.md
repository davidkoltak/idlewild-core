# idlewild-core

RTL project for a simple processing core experimenting 
with a single-threaded single-instruction ISA.  The only
defined instruction is a move.  Additional functionality
is implemented through special register read/writes.

The project uses Icarus Verilog (iverilog) and gtkwave
for simulation/validation.  The included example assembler
written in PYTHON is meant to contain only the minimum
necessary features to enable testcase generation.

 - David Koltak
