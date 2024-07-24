# Changelog

## [0.4.0](https://github.com/kodal/terraform-oci-free-tier-kubernetes/compare/v0.3.0...0.4.0) (2024-07-24)


### Features

* accept all connections ([9b38f32](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/9b38f325972587c338d2b2cf256f87e00200de8e))
* add default to availability domain variable ([#18](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/18)) ([f689bb2](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/f689bb214385b3c93cc8901508f7cbd47af9510d))
* add kubeadm config for metrics addresses ([#9](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/9)) ([1e5450e](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/1e5450e07846381c11176d3c665076fa7ae4fdb9))
* add oracle/oci in required providers ([#14](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/14)) ([c0724f2](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/c0724f26e78525eeb0dc939147b77c0c45d41f24))
* add packages ([f1b01ee](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/f1b01eef6e11443cff0170f5c0d3ba1103653aaa))
* add variable for availability domain ([#16](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/16)) ([0e974a0](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/0e974a039bbc1342863a310e957593a1dae90e1b))
* added availability domains output ([c969aed](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/c969aed53339923782238889231e051901381697))
* added cloud config, removed provisioner ([a748be3](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/a748be385a81402c6a864de10761308727e3d4c3))
* added compartment ([b16109a](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/b16109ae92b72ca8b2796b32e2cd673904abf65d))
* added compute instance ([3490e84](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/3490e8423c8f71c9e7153bd0bdd5547f0f4744ff))
* added description to variables and outputs ([63dfdef](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/63dfdefb940e7b7a997375b8c2554556d01b0d27))
* added dynamic lookup of image ([f2e27d7](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/f2e27d7747c8f08e95ea7332cfc96ca789c2df4b))
* added example ([6bfe95a](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/6bfe95abc19f940c4ad063102d6db5b471a00598))
* added file and remote-exec provisioner ([d32e034](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/d32e034fce36701e6bfdce7a548098b483e2bc54))
* added file provisioner ([6508c35](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/6508c35d9ba16c010a88b8eba18c54c5f6d87b6d))
* added initial oci config ([19c8413](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/19c84130a5dd5e34574cd9fb5c89e8c0f61c32dd))
* added kernel networking config ([7216f8b](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/7216f8b7d65c1ad846804791d0e7682c97ac71a1))
* added keys ([b372b03](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/b372b03f5b17598e1486f1faa0b2e83316e7883d))
* added kubeadm token module ([b83d3ce](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/b83d3ce380809852e198465985371f5308362ecb))
* added kubernetes setup ([0d0b545](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/0d0b5456dc11e6f407c524a9b20785ed4020b0c6))
* added name variable for naming compartment and kubeconfig ([5aae5c7](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/5aae5c75130da240e5d0f1a195ae496f07338ef5))
* added output of kubeconfig ([291e5c9](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/291e5c90c068587b9f1a1399a3f807f64776ec3f))
* added outputs ([4a966cf](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/4a966cf319a4d9aca3dffc054b9a8f93a9f2f695))
* added outputs for kubernetes certificates ([f530dde](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/f530ddeadb5bf8e6d0a069a54ae8a110b424d8f2))
* added package update and upgrade ([3e1dabb](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/3e1dabb770f7f245838da259c6344bce8f505ac9))
* added ports to public subnet security list ([8815a05](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/8815a050b73245c9cd2b7ac88bd4382b4d7156a4))
* added sources and packages ([a2861d6](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/a2861d69bbe13a5c98bb44fdd5df67f3ed613da9))
* added subnets and security lists ([e5032f9](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/e5032f9a05ef148b730f3ecb74113df95f17de45))
* added subnets for controlplane and worker nodes ([87a2011](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/87a201133366b73582c7b3edd8e068c9468a6fe3))
* added test output to cloud init ([76fb2dc](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/76fb2dceb9995ceecb239c6ee619ff3351c8d502))
* added variable configuration of cpu and memory ([a6213db](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/a6213dbb881b216d4afd07480ef5a6c3e0091b4b))
* added variable configuration of multiple instances ([bf2fff7](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/bf2fff7c8ec91da261c207023e935768b38580ed))
* added variable for ssh private key ([770c8d2](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/770c8d245503425dffacf424e8d0f6a848a35ac8))
* added virtual cloud network ([2bbbee3](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/2bbbee3b60c2ff6c28e75edc0181cc71bf5fce15))
* adopt firewall rules ([f999839](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/f999839832c7f7a9fc79bf6b33673b7cd4bca157))
* changed defaults in variables ([3018366](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/3018366901c3b9fcdf4a4f58746164f2294c1207))
* changed networing addon and subnet configuration ([8611c7e](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/8611c7e4db98639865b084bffb0a7f1e55bf0188))
* disable cloud init ([bd748f4](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/bd748f4815a512b9a1c17acf7fc434e3a2d4a952))
* disable creation of nat and service gateway ([9321e64](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/9321e64cddc894c137b25d649ed79896c699e638))
* disable swap ([aaf8b55](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/aaf8b55883f7d4236253d60c252b852683d7376f))
* enable cloud init ([62d422c](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/62d422c81300b528a6e5c52923bf338d945dac26))
* flush iptables ([127010c](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/127010c7337d032fd80d4fe13822cbeef01a7ffd))
* increase cpu and memory of instance ([b072af9](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/b072af9cf3d9b9e12cd7f61a9e88f19e2bf6679b))
* load kernel modules ([1021559](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/102155937405972d81bef86cbb236ba972d820d2))
* modified security rules ([c09ea26](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/c09ea26d73855b4fa70cbc501c7d338ff18060bc))
* preparation for oci-cloud-controller-manager ([aa088dd](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/aa088dd2317b38d80fb25e47fd4c7362846458b1))
* removed provider from module ([c5b8fa7](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/c5b8fa7c12f215db1357b2d7cf7b80c63e037877))
* removed version of kubeadm, kubelet and kubectl ([5f4781b](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/5f4781b5250c39646827156957c8cf42ec011438))
* set explicit private ip address ([8afd65c](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/8afd65cbc91b62fa5501b2524df4ee74a4a7a8b3))
* set kubeconfig outputs sensitive ([0d822ba](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/0d822ba27a32ce21a0cdf91a88406e5087290fbd))
* update apt sources ([#19](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/19)) ([640beed](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/640beed655184fba52d2cfb8a3e663dbb3683ebd))
* update iptables ([7e83875](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/7e8387537e58e008498cb9708048fa3406ee0d52))
* use keyid ([bbf2f41](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/bbf2f41289b11e4bd052942c813dc8487c80b85d))


### Bug Fixes

* added missing variable ([3d4a26a](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/3d4a26a6ae6c969b6fc2431cddf48c0828a198a4))
* containerd setup ([bea1413](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/bea141322ced42c7d3167005bb30dcca1db0692d))
* etcd listen metrics url ([#20](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/20)) ([eef34bc](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/eef34bc07b6ecba09c102054f9667dacc32d1635))
* fixed variable usage ([3f0b035](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/3f0b035efbedc38a2dc8ae8aeaaeda71bb0cb94a))
* fixed variable usage ([03bc09c](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/03bc09cbf8f2801780d0431073076693e4696fe2))
* ignore NumCPU error ([fe3e253](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/fe3e253e3b7df3f8903fd760b7596fc313552c88))
* malformed source ([c0b6454](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/c0b6454afac5f89dcf3028a9f60ae47dd78a4810))
* network interface name ([#2](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/2)) ([5c4e328](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/5c4e328428424206913a75813b38b6bec622ed39))
* path for templatefile ([6f51184](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/6f511842839ba49c3861fe38dc5c8482dc185578))
* path of kubeadm config ([9df1b32](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/9df1b32371e7aba8d456de041617abd346e732fe))
* remove duplicate base64 encoding from kubeconfig ([#21](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/21)) ([bb188ee](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/bb188ee5153b7f1a138051419681f361ba1509cb))
* replace deprecated template provider ([#3](https://github.com/kodal/terraform-oci-free-tier-kubernetes/issues/3)) ([26ad53f](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/26ad53fe278be669fb9b55d35a21d819237a25ef))
* type in compartment output ([84763c3](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/84763c3ee919210251080b75189cdee908b27930))
* typo in resource ([1c9b84f](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/1c9b84fbcc35f4d75c6a9570ed4f0880b506120b))
* use first availability domain ([6c1bf67](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/6c1bf671a165104fed9438cc9031647b77f2d2d5))
* use hardcoded path for root directory ([01a87cc](https://github.com/kodal/terraform-oci-free-tier-kubernetes/commit/01a87cc52e19d8d19809734ee5dbf25368b24dca))

## [0.3.0](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/compare/0.2.0...0.3.0) (2024-07-07)


### Features

* add default to availability domain variable ([#18](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/18)) ([f689bb2](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/f689bb214385b3c93cc8901508f7cbd47af9510d))
* add variable for availability domain ([#16](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/16)) ([0e974a0](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/0e974a039bbc1342863a310e957593a1dae90e1b))
* update apt sources ([#19](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/19)) ([640beed](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/640beed655184fba52d2cfb8a3e663dbb3683ebd))


### Bug Fixes

* etcd listen metrics url ([#20](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/20)) ([eef34bc](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/eef34bc07b6ecba09c102054f9667dacc32d1635))
* remove duplicate base64 encoding from kubeconfig ([#21](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/21)) ([bb188ee](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/bb188ee5153b7f1a138051419681f361ba1509cb))

## [0.2.0](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/compare/v0.1.2...0.2.0) (2024-03-30)


### Features

* add kubeadm config for metrics addresses ([#9](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/9)) ([1e5450e](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/1e5450e07846381c11176d3c665076fa7ae4fdb9))
* add oracle/oci in required providers ([#14](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/14)) ([c0724f2](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/c0724f26e78525eeb0dc939147b77c0c45d41f24))

## [0.1.2](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/compare/v0.1.1...v0.1.2) (2023-11-08)


### Bug Fixes

* replace deprecated template provider ([#3](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/3)) ([26ad53f](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/26ad53fe278be669fb9b55d35a21d819237a25ef))

## [0.1.1](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/compare/0.1.0...v0.1.1) (2023-05-18)


### Bug Fixes

* network interface name ([#2](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/issues/2)) ([5c4e328](https://github.com/robinlieb/terraform-oci-free-tier-kubernetes/commit/5c4e328428424206913a75813b38b6bec622ed39))
