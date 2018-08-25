# Coinbase Pro client for Rust
Supports SYNC and ASYNC operations.

## Api supported:
* SYNC:  done
* ASYNC: NONE


## API
- [x] Requests
- [ ] Pagination
- [x] Types
- Private
  - [x] Authentication
  - [x] Accounts
  - [x] Orders
  - [x] Fills
  - [ ] Deposits
  - [ ] Withdrawals
  - [ ] Payment Methods
  - [ ] Coinbase Accounts
  - [ ] Reports
  - [x] User Account
- [x] Market Data
  - [x] Products
  - [x] Currencies
  - [x] Time
- [] Websocket Feed
  - [ ] heartbeat
  - [ ] ticker
  - [ ] level2
  - [ ] user
  - [ ] matches
  - [ ] full

## FIX API
by request

## OrderBook
after Websocket

### test results
```
running 22 tests
test private::tests::test_get_account ... ok
test private::tests::test_get_account_holds ... ignored
test private::tests::test_get_account_hist ... ok
test private::tests::test_cancel_order ... ok
test private::tests::test_get_accounts ... ok
test private::tests::test_get_orders ... ignored
test private::tests::test_get_fills ... ok
test private::tests::test_new_order_ser ... ok
test private::tests::test_cancel_all ... ok
test private::tests::test_get_trailing_volume ... ok
test private::tests::test_get_order ... ok
test private::tests::test_set_order_limit_gtc ... ok
test public::tests::test_get_candles ... ok
test private::tests::test_set_order_limit ... ok
test private::tests::test_set_order_market ... ok
test public::tests::test_get_currencies ... ok
test public::tests::test_get_products ... ok
test public::tests::test_get_book ... ok
test public::tests::test_get_stats24h ... ok
test public::tests::test_get_ticker ... ok
test public::tests::test_get_trades ... ok
test public::tests::test_get_time ... ok

test result: FAILED. 21 passed; 0 failed; 2 ignored; 0 measured; 0 filtered out

```
