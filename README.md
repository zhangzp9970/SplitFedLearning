# SplitFedLearning

A split federated learning demo with Pytorch

Two clients and a server was implemented.

The [training-based Model Inversion Attack (MIA)](https://doi.org/10.1145/3319535.3354261) is implemented.

## Usage

Install Pytorch >=1.8.1 and [torchplus](https://github.com/zhangzp9970/torchplus)

Run main.py to train the classifier using split federated learning.

Run attack.py to perform MIA.

Run export.py to export both the private images and auxiliary images.

## License

Copyright © 2023 Zeping Zhang

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see [http://www.gnu.org/licenses/](https://gitee.com/link?target=http%3A%2F%2Fwww.gnu.org%2Flicenses%2F).
