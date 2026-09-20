# btcbot — Paper Trading Console (Online)

Live paper-trading dashboard for the **unified research-to-live** BTC system.

- **Mode:** paper only — venue orders are OFF
- **Engine:** fencing + write-ahead journal + portfolio coordinator
- **Docs:** see the main project `docs/ARCHITECTURE.md` / `INVARIANTS.md`
- **Regenerate:** `python scripts/paper_trade.py --market both --walk 400 && python scripts/build_dashboard.py`

Educational software. No real orders are sent from this dashboard.
