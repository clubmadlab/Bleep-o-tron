Bleep-o-tron
============

*Bleep-o-tron* is a polyphonic (4 voice) synthesiser kit using a phase modulation sound engine.

This repository contains a Patch Editor running as a Windows desktop app. It communicates with *Bleep-o-tron* over MIDI using System Exclusive messages. Typically it would be used with a USB-to-MIDI adapter that supports SysEx (not all of them do).

To install simply download the zip file and extract the contents to a target directory. No installer is needed - the app consists of a single executable and a DLL.

MIDI functionality is provided by DryWetMIDI - a .NET library to work with MIDI data and MIDI devices [copyright (c) 2018 Maxim Dobroselsky]. See https://github.com/melanchall/drywetmidi


Schematic, PCB, firmware and app by James Hutchby (c) 2022

james@madlab.org  
www.madlab.org  
@clubmadlab
