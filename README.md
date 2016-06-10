<img src="https://www.cloudbolt.io/wp-content/uploads/CloudBolt_hlogo_blue_cloud_w_text2-1.png" width="500">

# Summary
This is the Ruby api client for CloudBolt. It contains the src and gem file.

## Build
*gem build cloudbolt.spec

## Executables
*Provision (example)
 * cb_prov --proto https --host 'cloudbolt.example.com' --port 443 --user cloudbolt --pass 'password' --group-id 12 --env-id 29 --owner-id 2 --osbuild-id 1 --cf vmware_disk_type="Thin Provision",sc_nic_0="VLAN 27 (DHCP)",mem_size="1 GB",vmware_datastore="NAS-NFS",cpu_cnt="1",vmware_cluster="C01",expiration_date="2016-07-27",link_clone="True" --hostname "rubyapi007" --wait

*Decom (example)
 * cb_decom --proto https --host 'cloudbolt.example.com' --port 443 --user cloudbolt --pass 'password' --env-id 29 --group-id 12 --server-ids 434 --wait

## Ruby Class
*TBD

## LICENSE
Use of this software is governed by the CloudBolt EULA. Contributions to this
project are goverened by the CONTRIBUTING file and the MIT License, below.

## CONTRIBUTING

You may submit pull requests to this project so that they can be incorporated
back into CloudBolt. By submitting a pull request for this project, you agree
to license your contribution under the MIT license to this project.

The MIT License (MIT)

Copyright (c) 2016 CloudBolt Software

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
