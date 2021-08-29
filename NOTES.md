
## TODO
  - [ ] mocha timeouts are annoying! Seems to be related to downloading solc.
        Maybe there's a way to cache this for CI


## Tests marked skipped

Use command: `rg --vimgrep "\.skip\w*?\("`

packages/core/test/ethpm.js:13:9:describe.skip("EthPM integration", function () {
packages/core/lib/testing/Test.js:344:21:      Mocha.describe.skip("Contract: " + name, function () {
packages/interface-adapter/test/quorum-decodeParameters.test.ts:47:5:  it.skip("throws an 'Out of Gas?' error when decoding an empty byte w/ quorum=false", async function() {
packages/core/test/lib/services/analytics/google-analytics.js:67:7:    it.skip("sets user-level configuration variables", function() {
packages/deployer/test/deployer.js:277:7:    it.skip("waits for confirmations", async function() {
packages/truffle/test/scenarios/commands/ethpm.js:38:5:  it.skip("Can locate all the sources to publish", function(done) {
packages/preserve-to-buckets/test/buckets.test.ts:8:9:describe.skip("preserve", () => {
packages/preserve-to-filecoin/test/filecoin.test.ts:198:13:    describe.skip("Lotus policy (does not work with Ganache)", () => {
packages/contract-tests/test/methods.js:489:7:    it.skip("errors with a revert reason", async function () {
packages/contract-tests/test/methods.js:541:11:  describe.skip("web3 wallet", function () {
packages/compile-solidity/test/test_parser.js:64:5:  it.skip("should return correct imports with docker solc [ @native ]", () => {
packages/compile-solidity/test/test_JSparser.js:26:5:  it.skip("resolves imports when using solcjs parser instead of docker [ @native ]", async () => {
packages/compile-solidity/test/test_supplier.js:15:9:describe.skip("CompilerSupplier", function () {

## Test marked only
Use command: `rg --vimgrep "\.only\w*?\("`

There are 0 `only` tests
