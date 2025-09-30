# Dynamics of temporal influence on polarised networks
This repository contains the data to build the networks analysed on the paper "Dynamics of temporal influence on polarised networks". The paper is available on [arXiv](https://arxiv.org/abs/2507.17177).

## File description
The file `BandNet1_t1.csv` contains the edges of BandNet1 in time slice 1.

The file `BandNet1_t2.csv` contains the edges of BandNet1 in time slice 2.

The file `BandNet1_t3.csv` contains the edges of BandNet1 in time slice 3.

The file `BandNet1_t4.csv` contains the edges of BandNet1 in time slice 4.

The file `BandNet2_t1.csv` contains the edges of BandNet2 in time slice 1.

The file `BandNet2_t2.csv` contains the edges of BandNet2 in time slice 2.

The file `BandNet2_t3.csv` contains the edges of BandNet2 in time slice 3.

The file `BandNet2_t4.csv` contains the edges of BandNet2 in time slice 4.

The file `BandNet3_t1.csv` contains the edges of BandNet3 in time slice 1.

The file `BandNet3_t2.csv` contains the edges of BandNet3 in time slice 2.

The file `BandNet3_t3.csv` contains the edges of BandNet3 in time slice 3.

The file `BandNet3_t4.csv` contains the edges of BandNet3 in time slice 4.

The file `RT8_t1_an.csv` contains the edges of the RT8 original network in time slice 1.

The file `RT8_t2_an.csv` contains the edges of the RT8 original network in time slice 2.

The file `RT8_t3_an.csv` contains the edges of the RT8 original network in time slice 3.

The file `RT8_t4_an.csv` contains the edges of the RT8 original network in time slice 4.

The file `RT8_config_t1_an.csv` contains the edges of the configuration model with the same degree distribution as the RT8 network in time slice 1.

The file `RT8_config_t2_an.csv` contains the edges of the configuration model with the same degree distribution as the RT8 network in time slice 2.

The file `RT8_config_t3_an.csv` contains the edges of the configuration model with the same degree distribution as the RT8 network in time slice 3.

The file `RT8_config_t4_an.csv` contains the edges of the configuration model with the same degree distribution as the RT8 network in time slice 4.

## File structure
The files `BandNet[]_t[].csv` contain four columns:
- `from`: the node in one of the ends of the edge (note BandNet networks are undirected).
- `to`: the node in the other end of the edge (note BandNet networks are undirected).
- `comm_from`: the community membership of the `from` node.
- `comm_to`: the community membership of the `to` node.

The files `RT8_t[]_an.csv` and `RT8_config_t[]_an.csv` contain four columns:
- `from`: the anonymized node in which the edge begins.
- `to`: the anonymized node in which the edge ends.
- `comm_from`: the community membership of the `from` node.
- `comm_to`: the community membership of the `to` node.

