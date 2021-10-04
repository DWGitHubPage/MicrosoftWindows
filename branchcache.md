## Working with BranchCache.

BranchCache works in one of two modes: Distributed or Hosted Mode. Distributed allows clients to request cached 
content from one another, while Hosted Mode centralizes the cache on a BranchCache server. Distributed Mode 
should be used when there are fewer than 50 clients on the branch office network.


### Configuring BranchCache

Steps:

1. Click the SVMs tab.

2. Select the SVM, and then click Manage.

3. Click the SVM Settings tab.

4. In the BranchCache tab, click Set Up.

5. In the BranchCache Setup dialog box, enter the following information: Specify the path to the hash store.

6. Click Set Up.


### BranchCache in Powershell:

### To check the status:

Get-WSSBranchCacheStatus

### To turn on BranchCache:

Enable-WSSBranchCache

### To turn off BranchCache:

Disable-WSSBranchCache


### BranchCache files are stored in:

C:WindowsServiceProfilesNetworkServiceAppDataLocalPeerDistRepub
