# Changelog

## Unreleased

## 0.26.3 (June 11, 2021)

### Breaking Changes

- Remove `currentValidationStart` from response of `dna_epoch` RPC method ([#706](https://github.com/idena-network/idena-go/pull/706))  

### Changes

- Get rid of double block processing while inserting a block into the chain ([#704](https://github.com/idena-network/idena-go/pull/704) & [#708](https://github.com/idena-network/idena-go/pull/708))
- Add `startBlock` to response of `dna_epoch` RPC method ([#706](https://github.com/idena-network/idena-go/pull/706))
- Upgrade to GitHub-native Dependabot ([#683](https://github.com/idena-network/idena-go/pull/683))
- Update iavl and protobuf deps ([#696](https://github.com/idena-network/idena-go/pull/696))
- Update deps ([#698](https://github.com/idena-network/idena-go/pull/698) & [#699](https://github.com/idena-network/idena-go/pull/699) & [#700](https://github.com/idena-network/idena-go/pull/700) & [#701](https://github.com/idena-network/idena-go/pull/701) & [#707](https://github.com/idena-network/idena-go/pull/707))
- Add CHANGELOG.md ([#702](https://github.com/idena-network/idena-go/pull/702))

## 0.26.2 (May 26, 2021)

### Bug Fixes

- Fix invitation reward calculation ([#692](https://github.com/idena-network/idena-go/pull/692))

## 0.26.1 (May 11, 2021)

### Bug Fixes

- Fix offline detector flags validation ([#686](https://github.com/idena-network/idena-go/pull/686))

## 0.26.0 (May 7, 2021)

### Fork (Upgrade 5)

- Encourage early invitations ([#671](https://github.com/idena-network/idena-go/pull/671))
- Check 5 sequential blocks without ceremonial txs to finish the validation ceremony ([#672](https://github.com/idena-network/idena-go/pull/672))
- Implement delayed offline penalties ([#674](https://github.com/idena-network/idena-go/pull/674))
- Burn 5/6 of invitee stake in KillInviteeTx ([#676](https://github.com/idena-network/idena-go/pull/676))

### Changes

- Add new tx type to store data to IPFS ([#670](https://github.com/idena-network/idena-go/pull/670))

### Bug Fixes

- Fix events for pool rewards in oracle voting ([#669](https://github.com/idena-network/idena-go/pull/669))

## 0.25.3 (Apr 30, 2021)

### Changes

- Save own mempool transactions to disk ([#675](https://github.com/idena-network/idena-go/pull/675) & [#679](https://github.com/idena-network/idena-go/pull/679) & [#680](https://github.com/idena-network/idena-go/pull/680) & [#681](https://github.com/idena-network/idena-go/pull/681))
- Add flip keywords API ([#678](https://github.com/idena-network/idena-go/pull/678))

### Bug Fixes

- Fix data races ([#667](https://github.com/idena-network/idena-go/pull/667))
- Trim whitespace around API key from [@busimus](https://github.com/busimus) ([#668](https://github.com/idena-network/idena-go/pull/668))

## 0.25.2 (Apr 1, 2021)

Finish voting transactions will be enabled on the next seamless fork.

### Changes

- Temporary disable finish oracle voting transactions due to bug ([#665](https://github.com/idena-network/idena-go/pull/665))

## 0.25.1 (Mar 27, 2021)

### Changes

- Respect delegation switch in RPC calls ([#657](https://github.com/idena-network/idena-go/pull/657))

## 0.25.0 (Mar 22, 2021)

### Fork (Upgrade 4)

- Introduce pools ([#631](https://github.com/idena-network/idena-go/pull/631))
- Update contracts ([#649](https://github.com/idena-network/idena-go/pull/649))
- Increase flip rewards, decrease invite rewards ([#651](https://github.com/idena-network/idena-go/pull/651))
- Burn 5/6 of invitee stake in KillInviteeTx ([#676](https://github.com/idena-network/idena-go/pull/676))

### Changes

- Increase file descriptor limit ([#653](https://github.com/idena-network/idena-go/pull/653))
- Update deps ([#645](https://github.com/idena-network/idena-go/pull/645) & [#648](https://github.com/idena-network/idena-go/pull/648))

### Bug Fixes

- Fix build on linux ([#650](https://github.com/idena-network/idena-go/pull/650) & [#654](https://github.com/idena-network/idena-go/pull/654))