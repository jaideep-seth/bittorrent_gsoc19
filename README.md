
# Aim:

* My mentors and I aim to integrate within PyOpenWorm a P2P FileSharing framework with features like access control and data integrity checks to ensure the quality of content being shared. [Project statement and point of integration](https://neurostars.org/t/gsoc-project-idea-16-1-peer-to-peer-file-and-metadata-sharing-for-openworm-data-management/3386)


* Our highest priority is to have no additional installation steps and minimal user effort to utilize this framework. We want no change to the manner in which [PyOpenWorm currently installs](https://github.com/openworm/PyOpenWorm/blob/dev/INSTALL.md), while also not leaving the Command Line Interface(CLI).


## What has been done?

* Merged code for creating a [torrent_file_informational.](https://github.com/openworm/PyOpenWorm/pull/424) 

* Packaged a BitTorrent Client, [now available on PyPI.](https://pypi.org/project/torrent-client/) This is its [Github repository](https://github.com/jaideep-seth/Torrent_client_gsoc19).

* [Merged Files](https://github.com/openworm/OpenWormData/pull/4) for access control features of the framework.

* The stand-alone repository for describing the end to end process of the framework, [created within OpenWorm](https://github.com/openworm/bt-gsoc-2019).

* [Made a PR](https://github.com/openworm/PyOpenWorm/pull/449) to Subclass DataSourceLoader and implement its load method in BitTorrentDataSourceDirLoader. Setup and access control dependencies of the BitTorrent Client are included alongwith an
integration test.  

* Setup a [Ubuntu container with an Elastic IP on AWS](http://13.235.204.78) , this server is implemented to improve user experience by avoiding required installations needed for seeding contents to BitTorrent.

* [Merged the documentation](https://github.com/openworm/PyOpenWorm/pull/451) for the process of Uploading and Downloading desired contents.

### Prerequisites

What things you need to install the software and how to install them

## Authors

* **Billie Thompson** - *Initial work* - [Instance](http://13.235.204.78)





* [PyOpenWorm commits](https://github.com/openworm/PyOpenWorm/commits?author=jaideep-seth)

* [OpenWormData commits](https://github.com/openworm/OpenWormData/commits?author=jaideep-seth)

* [PyOpenWorm Pull Requests](https://github.com/openworm/PyOpenWorm/pulls/jaideep-seth)

* [OpenWorm GSoC19 Repository](https://github.com/openworm/bt-gsoc-2019)

* [PyPI package repository](https://github.com/jaideep-seth/Torrent_client_gsoc19)

* [Client available on PyPI](https://pypi.org/project/torrent-client/)
