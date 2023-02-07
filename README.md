# WATT-Overview

This repository provides an overview of all artifacts available, used in the paper WATT.

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
