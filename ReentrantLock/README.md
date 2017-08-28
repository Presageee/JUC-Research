# Source Guide

### Sync's Define
line 116 - 192

### FairSync's Define
line 219 - 249

### NonFairSync's Define
line 197 - 214


### Init And Setting Sync
1. method ReentrantLock line 255 - 257
2. method ReentrantLock(boolean fair) line 265 - 267

### Nonfair Lock
1. method ReentrantLock.lock line 283 - 285
2. method NonFairSync.lock line 204 - 209
3. method NonFairSync.tryAcquire line 211 - 213
4. method Sync.nonfairTryAcquire line 129 - 146


### Fair Lock
1. method ReentrantLock.lock line 283 - 285
2. method FairSync.tryAcquire line 231 - 249


### unLock
1. method unlock line 456 - 458
2. method Sync.tryRelease line 148 - 159

happy to research!