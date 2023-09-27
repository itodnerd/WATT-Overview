# WATT-Overview

This repository provides an overview of all artifacts available for WATT.

## VLDB 2023

For the VLDB 2023 you can access our [paper](https://www.vldb.org/pvldb/vol16/p3323-vohringer.pdf) and a video of an early stage of the [presentation](https://youtu.be/ZwQFDwTbqS4?).

The [presentation](VLDB2023/presentation.pdf) itself and the [transcript](VLDB2023/presentation_transcript.md) can be found in the directory [VLDB2023](VLDB2023).

## Source-Code

WATT has been implemented in LeanStore:

https://github.com/leanstore/leanstore/tree/WATT

The most important parts are

1. Tracker in the [BufferFrame](https://github.com/leanstore/leanstore/blob/WATT/backend/leanstore/storage/buffer-manager/BufferFrame.hpp)
2. Replacement in the  [Page Evictor](https://github.com/leanstore/leanstore/blob/WATT/backend/leanstore/storage/buffer-manager/PageProviderThread.cpp)

## Simulation

We compared WATT with other strategies based on this simulation:

https://github.com/itodnerd/WATT-simulate

## Traces

For the simulation we used these traces:

https://github.com/itodnerd/WATT-traces/tree/main/WATT_competition_traces
