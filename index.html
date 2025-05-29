<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Peapods Dashboard</title>
  <link rel="stylesheet" href="https://cdn.datatables.net/1.13.6/css/jquery.dataTables.min.css" />
  <style>
    .network-img {
      vertical-align: middle;
      margin-right: 6px;
    }
    .totals-row {
      font-weight: bold;
      background: #eee;
    }
    body {
      font-family: sans-serif;
      background: #fafcff;
    }
    .container {
      width: 95%;
      max-width: none;
      margin: 40px auto;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 2px 16px #0001;
      padding: 32px 32px 24px;
    }
    h1,
    h2 {
      margin-bottom: 8px;
    }
    table {
      margin-bottom: 32px;
    }
    .dataTables_wrapper {
      margin-bottom: 32px;
    }
    #asset-summary-table {
      width: 50%;
      margin-top: 24px;
      border-collapse: collapse;
    }
    #asset-summary-table th,
    #asset-summary-table td {
      padding: 6px 12px;
      border: 1px solid #ddd;
    }
    #asset-summary-table th {
      background: #f4f4f4;
      font-weight: bold;
    }
    #asset-summary-table td {
      text-align: right;
    }
    #asset-summary-table td:first-child {
      text-align: left;
    }
  </style>
</head>
  <div style="background:#fff3cd;color:#856404;border:1px solid #ffeeba;padding:12px 20px;margin:20px auto;text-align:center;border-radius:8px;max-width:75%;font-size:0.95em;">
    <strong>Disclaimer:</strong> This dashboard is not an official tool. It is for informational purposes only. Data accuracy is not guaranteed and users must verify information independently.
  </div>
  <h1
    style="
      margin: 32px auto 22px auto;
      padding: 0;
      font-size: 2.2em;
      font-weight: 900;
      letter-spacing: -1px;
      color: #123c22;
      text-align: center;
      max-width: 900px;
    "
  >
    Peapods Dashboard
  </h1>
  <div class="container">
    <div id="address-ui" style="margin-bottom: 32px;">
      <div id="address-ui-message" style="margin-bottom: 14px; color: #555; font-size: 1.01em;"></div>
      <div id="address-list" style="margin-bottom: 18px;"></div>
      <form
        id="add-address-form"
        style="
          display: flex;
          gap: 12px;
          align-items: center;
          max-width: 420px;
        "
      >
        <input
          type="text"
          id="new-address"
          placeholder="Enter a wallet address"
          style="
            flex: 1;
            padding: 8px 12px;
            border-radius: 8px;
            border: 1px solid #ddd;
            font-size: 1.05em;
          "
          required
        />
        <button
          type="submit"
          style="
            padding: 8px 18px;
            border-radius: 8px;
            background: #00653a;
            color: white;
            font-weight: bold;
            cursor: pointer;
            border: none;
          "
        >
          Add
        </button>
      </form>
    </div>

    <div id="positions-section">
      <h2>LVF Positions</h2>
      <table id="positions" class="display" style="width: 100%">
        <thead>
          <tr>
            <th>Chain</th>
            <th>Address</th>
            <th>Symbol</th>
            <th>Name</th>
            <th>Health</th>
            <th>liq price $</th>
            <th>VF APR</th>
            <th>Borrowed assets</th>
            <th>Underlying from pTKN</th>
            <th>Underlying from Pair Asset</th>
            <th>Collateral Value (USD)</th>
            <th>Net Position (USD)</th>
          </tr>
        </thead>
        <tbody></tbody>
        <tfoot>
          <tr class="totals-row">
            <td colspan="7"></td>
            <td id="borrowed-total" style="text-align: right; font-weight: bold;"></td>
            <td colspan="2"></td>
            <td id="positions-total" style="text-align: right; font-weight: bold;"></td>
            <td id="net-total" style="text-align: right; font-weight: bold;"></td>
          </tr>
        </tfoot>
      </table>
      <div
        id="positions-summary"
        style="
          padding: 16px;
          background: #f9f9f9;
          border: 1px solid #ddd;
          margin-top: -16px;
          display: inline-block;
          margin-left: auto;
          margin-right: auto;
        "
      >
        <h3>Underlying Asset Summary</h3>
        <table id="asset-summary-table">
          <thead>
            <tr>
              <th>Asset</th>
              <th>Total Amount</th>
              <th>USD Value</th>
            </tr>
          </thead>
          <tbody></tbody>
        </table>
      </div>
    </div>

    <div id="pods-section">
      <h2>Pods</h2>
      <table id="pods" class="display" style="width: 100%">
        <thead>
          <tr>
            <th>Chain</th>
            <th>Address</th>
            <th>Symbol</th>
            <th>Name</th>
            <th>pTKN Balance</th>
            <th>pTKN Value</th>
            <th>spTKN Balance</th>
            <th>spTKN Value</th>
            <th>Unclaimed PEAS</th>
            <th>Unclaimed PEAS value</th>
          </tr>
        </thead>
        <tbody></tbody>
        <tfoot>
          <tr class="totals-row">
            <td colspan="5"></td>
            <td id="pods-total"></td>
            <td></td>
            <td id="pods-sptkn-total"></td>
            <td>Total Unclaimed</td>
            <td id="pods-unclaimed-total"></td>
          </tr>
        </tfoot>
      </table>
    </div>

    <div id="lending-section">
      <h2>Lending pairs</h2>
      <table id="lending" class="display" style="width: 100%">
        <thead>
          <tr>
            <th>Chain</th>
            <th>Address</th>
            <th>Symbol</th>
            <th>Name</th>
            <th>Asset</th>
            <th>Balance</th>
            <th>Value</th>
            <th>Utilization</th>
            <th>Lender APR</th>
            <th>Lender APY</th>
            <th>Daily revenue (APR)</th>
          </tr>
        </thead>
        <tbody></tbody>
        <tfoot>
          <tr class="totals-row">
            <td colspan="6" style="text-align: right">Total</td>
            <td id="lending-total"></td>
            <td colspan="3"></td>
            <td id="lending-daily-total"></td>
          </tr>
        </tfoot>
      </table>
    </div>
  </div>
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
  <script src="https://cdn.datatables.net/1.13.6/js/jquery.dataTables.min.js"></script>
  <script>
    // --- Address UI, LocalStorage, and Dashboard Logic ---
    var totals = {
      positions: 0,
      pods: 0,
      spods: 0,
      unclaimed: 0,
      lending: 0,
      lending_daily: 0,
      borrowed: 0,
      collateral: 0,
    };

    function getDashboardAddresses() {
      try {
        let arr = localStorage.getItem("peapods_addresses");
        if (!arr) return [];
        return JSON.parse(arr) || [];
      } catch (e) {
        return [];
      }
    }

    let loadPeapodsDashboard = async function () {
      const addresses = getDashboardAddresses();
      const chains = ["ethereum", "base", "arbitrum", "sonic"];
      const networks = {
        ethereum: {
          explorer: "https://etherscan.io/address/",
          image: "ethereum.ico",
        },
        base: { explorer: "https://basescan.org/address/", image: "base.svg" },
        arbitrum: {
          explorer: "https://arbiscan.io/address/",
          image: "arbitrum.svg",
        },
        sonic: { explorer: "https://sonicscan.org/address/", image: "sonic.ico" },
      };

      function shortERC20(address) {
        return address.substr(0, 6) + "..." + address.substr(-6);
      }

      // Clear tables if no addresses
      if (addresses.length === 0) {
        if ($.fn.DataTable.isDataTable("#positions"))
          $("#positions").DataTable().clear().draw();
        if ($.fn.DataTable.isDataTable("#pods")) $("#pods").DataTable().clear().draw();
        if ($.fn.DataTable.isDataTable("#lending"))
          $("#lending").DataTable().clear().draw();
        $("#positions-total").text("");
        $("#pods-total").text("");
        $("#pods-unclaimed-total").text("");
        $("#lending-total").text("");
        $("#lending-daily-total").text("");
        updateGrandTotal({
          positions: 0,
          pods: 0,
          spods: 0,
          lending: 0,
        });
        return;
      }

      let positionsData = [];
      let podsData = [];
      let lendingData = [];
      totals.positions = 0;
      totals.pods = 0;
      totals.spods = 0;
      totals.unclaimed = 0;
      totals.lending = 0;
      totals.lending_daily = 0;
      totals.borrowed = 0;
      totals.collateral = 0;

      let countedPositions = new Set();
      let assetSummary = {};
      for (let addr of addresses) {
        for (let chain of chains) {
          try {
            const resp = await fetch(
              `https://peas-api-9326490b149b.herokuapp.com/${chain}/wallet/${addr}`
            );
            const data = await resp.json();
            let explorer = networks[chain]?.explorer || "https://sonicscan.org/address/";

            // LVF Positions
            if (data.positions) {
              data.positions.forEach((p) => {
                let uniqueKey = `${addr}_${chain}_${p.id}_${
                  p.lending_pair?.address ?? ""
                }`;
                if (countedPositions.has(uniqueKey)) return;
                countedPositions.add(uniqueKey);

                const decimals = p.lending_pair.asset?.decimals || 18;
                let total_borrowed = 0;
let borrowed_usd = 0;
if (Number(p.lending_pair.total_borrow_shares) > 0) {
  total_borrowed =
    (BigInt(p.user_borrow_shares) * BigInt(p.lending_pair.total_borrow_amount)) / BigInt(p.lending_pair.total_borrow_shares);
  total_borrowed = Number(total_borrowed) / (10 ** decimals);
  borrowed_usd = total_borrowed * (p.lending_pair.asset?.price_usd || 0);
  totals.borrowed += borrowed_usd;                }
                let spTKN = (Number(p.collateral_balance) / 1e18) * Number(p.lending_pair.asptkn_cbr);
                let lp_token_supply = Number(
                  p.lending_pair.pod.liquidity_pool.lp_token_supply
                ) / 1e18;
                let share = lp_token_supply > 0 ? spTKN / lp_token_supply : 0;

                let ptkn_balance =
                  share * (Number(p.lending_pair.pod.liquidity_pool.ptkn_balance) / 1e18);
                let ptkn_underlying = ptkn_balance * Number(p.lending_pair.pod.cbr);
                let ptkn_underlying_usd =
                  ptkn_underlying * Number(p.lending_pair.pod.assets[0].price_usd);

                let pair_balance =
                  share * (Number(p.lending_pair.pod.liquidity_pool.pair_balance) / 10 ** decimals);
                let asset_usdc = pair_balance * Number(p.lending_pair.cbr);
                let asset_usd = asset_usdc * (p.lending_pair.asset?.price_usd || 1);

                // Calculate collateral and net
                let collateral_value_usd =
                  (isFinite(ptkn_underlying_usd) ? ptkn_underlying_usd : 0) +
                  (isFinite(asset_usd) ? asset_usd : 0);
                let net_position_usd = collateral_value_usd - borrowed_usd;
                // accumulate totals
                totals.collateral += collateral_value_usd;

                let row = [
                  chain.charAt(0).toUpperCase() + chain.slice(1),
                  `<a href="${explorer}${addr}" target="_blank">${shortERC20(addr)}</a>`,
                  p.lending_pair?.pod?.symbol ? `${p.lending_pair.pod.symbol}#${p.id}` : `#${p.id}`,
                  p.lending_pair?.pod?.name || "-",
                  Number(p.health_factor) ? Number(p.health_factor).toFixed(2) : "-",
                  typeof p.liquidation_price_usd !== "undefined" &&
                  p.liquidation_price_usd !== null &&
                  !isNaN(p.liquidation_price_usd)
                    ? "$ " +
                      Number(p.liquidation_price_usd).toLocaleString("en-US", {
                        maximumFractionDigits: 2,
                      })
                    : "-",
                  Number(p.vf_apr) ? (p.vf_apr * 100).toFixed(2) + "%" : "-",
                  (isFinite(total_borrowed) ? total_borrowed.toLocaleString("en-US", { maximumFractionDigits: 2 }) : "-") + ` ${p.lending_pair?.asset?.symbol || ""}` + (borrowed_usd ? `<br />($${borrowed_usd.toLocaleString("en-US", { maximumFractionDigits: 2 })})` : ""),
                  (isFinite(ptkn_underlying)
                    ? ptkn_underlying.toLocaleString("en-US", { maximumFractionDigits: 2 })
                    : "-") +
                    ` ${p.lending_pair.pod.assets[0].symbol}` +
                    (isFinite(ptkn_underlying_usd)
                      ? `<br />($${ptkn_underlying_usd.toLocaleString("en-US", {
                          maximumFractionDigits: 2,
                        })})`
                      : ""),
                  (isFinite(asset_usdc)
                    ? asset_usdc.toLocaleString("en-US", { maximumFractionDigits: 2 })
                    : "-") +
                    ` ${p.lending_pair?.asset?.symbol || ""}` +
                    (isFinite(asset_usd)
                      ? `<br />($${asset_usd.toLocaleString("en-US", { maximumFractionDigits: 2 })})`
                      : ""),
                  "$ " + collateral_value_usd.toLocaleString("en-US", { maximumFractionDigits: 2 }),
                  "$ " + net_position_usd.toLocaleString("en-US", { maximumFractionDigits: 2 }),
                ];
                positionsData.push(row);
                // accumulate summary
                let sym = p.lending_pair.pod.assets[0].symbol;
                assetSummary[sym] = assetSummary[sym] || { amount: 0, usd: 0 };
                assetSummary[sym].amount += ptkn_underlying;
                assetSummary[sym].usd += ptkn_underlying_usd;
                let pairSym = p.lending_pair.asset.symbol;
                assetSummary[pairSym] = assetSummary[pairSym] || { amount: 0, usd: 0 };
                assetSummary[pairSym].amount += asset_usdc;
                assetSummary[pairSym].usd += asset_usd;
                if (Number(p.ptkn_collateral_value_usd)) totals.positions += Number(p.ptkn_collateral_value_usd);
              });
            }

            // Pods
            if (data.pods) {
              data.pods.forEach((p) => {
                let ptkn_bal = p.ptkn_balance / 10 ** p.decimals;
                let sptkn_bal = p.sptkn_balance / 1e18;
                let ptkn_val = ptkn_bal * p.ptkn_price_usd;
                let sptkn_val = sptkn_bal * p.sptkn_price_usd;
                let unclaimed =
                  (p.rewards?.[0]?.unclaimed_balance || 0) / (10 ** (p.rewards?.[0]?.decimals || 18));
                let unclaimed_val = unclaimed * (p.rewards?.[0]?.price || 0);

                let row = [
                  chain.charAt(0).toUpperCase() + chain.slice(1),
                  `<a href="${explorer}${addr}" target="_blank">${shortERC20(addr)}</a>`,
                  p.symbol || "-",
                  p.name || "-",
                  ptkn_bal?.toFixed(8) || "0",
                  "$ " + (ptkn_val?.toFixed(2) || "0.00"),
                  sptkn_bal?.toFixed(8) || "0",
                  "$ " + (sptkn_val?.toFixed(2) || "0.00"),
                  unclaimed?.toFixed(2) || "0.00",
                  "$ " + (unclaimed_val?.toFixed(2) || "0.00"),
                ];
                podsData.push(row);
                totals.pods += ptkn_val || 0;
                totals.spods += sptkn_val || 0;
                totals.unclaimed += unclaimed_val || 0;
              });
            }

            // Lending pairs
            if (data.lending_pairs) {
              data.lending_pairs.forEach((p) => {
                let bal = p.balance / 10 ** p.decimals;
                let val = bal * p.cbr * p.asset.price_usd;
                let daily = val * p.supplier_apr / 365;

                let row = [
                  chain.charAt(0).toUpperCase() + chain.slice(1),
                  `<a href="${explorer}${addr}" target="_blank">${shortERC20(addr)}</a>`,
                  p.pod?.symbol || "-",
                  p.pod?.name || "-",
                  p.asset?.symbol || "-",
                  bal?.toLocaleString("en-US", { maximumFractionDigits: 2 }) || "0",
                  "$ " + (val?.toLocaleString("en-US", { maximumFractionDigits: 2 }) || "0.00"),
                  (p.utilization ? (p.utilization * 100).toFixed(1) : "0") + "%",
                  (p.supplier_apr ? (p.supplier_apr * 100).toFixed(1) : "0") + "%",
                  (p.lender_apy ? (p.lender_apy * 100).toFixed(1) : "0") + "%",
                  "$ " + (daily?.toFixed(2) || "0.00"),
                ];
                lendingData.push(row);
                totals.lending += val || 0;
                totals.lending_daily += daily || 0;
              });
            }
          } catch (e) {
            console.error(`Error fetching ${chain} for ${addr}`, e);
          }
        }
      }

      // Positions DataTable
      if ($.fn.DataTable.isDataTable("#positions")) {
        $("#positions").DataTable().clear().rows.add(positionsData).draw();
      } else {
        $("#positions").DataTable({
          data: positionsData,
          paging: false,
          searching: false,
          order: [[5, "desc"]],
        });
      }

      // Set totals in positions footer
      $("#borrowed-total").text("$ " + totals.borrowed.toLocaleString("en-US", { maximumFractionDigits: 0 }));
      $("#positions-total").text("$ " + totals.collateral.toLocaleString("en-US", { maximumFractionDigits: 0 }));
      $("#net-total").text(
        "$ " + (totals.collateral - totals.borrowed).toLocaleString("en-US", { maximumFractionDigits: 0 })
      );

      // Pods DataTable
      if ($.fn.DataTable.isDataTable("#pods")) {
        $("#pods").DataTable().clear().rows.add(podsData).draw();
      } else {
        $("#pods").DataTable({
          data: podsData,
          paging: false,
          searching: false,
          order: [[5, "desc"]],
        });
      }
      $("#pods-total").text("$ " + totals.pods.toLocaleString("en-US", { maximumFractionDigits: 2 }));
      $("#pods-sptkn-total").text("$ " + totals.spods.toLocaleString("en-US", { maximumFractionDigits: 2 }));
      $("#pods-unclaimed-total").text("$ " + totals.unclaimed.toLocaleString("en-US", { maximumFractionDigits: 2 }));

      // Lending DataTable
      if ($.fn.DataTable.isDataTable("#lending")) {
        $("#lending").DataTable().clear().rows.add(lendingData).draw();
      } else {
        $("#lending").DataTable({
          data: lendingData,
          paging: false,
          searching: false,
          order: [[6, "desc"]],
        });
      }
      $("#lending-total").text("$ " + totals.lending.toLocaleString("en-US", { maximumFractionDigits: 2 }));
      $("#lending-daily-total").text("$ " + totals.lending_daily.toLocaleString("en-US", { maximumFractionDigits: 2 }));

      // Make asset summary table
      let tbody = $("#asset-summary-table tbody");
      tbody.empty();
      Object.entries(assetSummary).forEach(([sym, data]) => {
        tbody.append(
          `<tr>
            <td style="text-align:left;">${sym}</td>
            <td style="text-align:right;">${data.amount.toLocaleString("en-US", {
              minimumFractionDigits: 2,
              maximumFractionDigits: 2,
            })}</td>
            <td style="text-align:right;">$${data.usd.toLocaleString("en-US", {
              minimumFractionDigits: 0,
              maximumFractionDigits: 0,
            })}</td>
          </tr>`
        );
      });

      // Update grand total display
      updateGrandTotal(totals);
    }; // End of loadPeapodsDashboard

    document.addEventListener("DOMContentLoaded", function () {
      const LS_KEY = "peapods_addresses";
      const addressListDiv = document.getElementById("address-list");
      const addForm = document.getElementById("add-address-form");
      const addInput = document.getElementById("new-address");
      const messageDiv = document.getElementById("address-ui-message");
      const tables = [
        { id: "positions", section: "positions-section" },
        { id: "pods", section: "pods-section" },
        { id: "lending", section: "lending-section" },
      ];

      // initial hide tables
      tables.forEach((tbl) => {
        let section = document.getElementById(tbl.section);
        if (section) section.style.display = "none";
      });

      function getStoredAddresses() {
        try {
          const val = localStorage.getItem(LS_KEY);
          if (!val) return [];
          return JSON.parse(val) || [];
        } catch (e) {
          return [];
        }
      }
      function storeAddresses(arr) {
        localStorage.setItem(LS_KEY, JSON.stringify(arr));
      }

      function renderAddressList() {
        const addrs = getStoredAddresses();
        addressListDiv.innerHTML = "";
        if (addrs.length === 0) {
          messageDiv.innerHTML = "<b>Add a wallet address below to get started.<\/b>";
          tables.forEach((tbl) => {
            let section = document.getElementById(tbl.section);
            if (section) section.style.display = "none";
          });
          loadPeapodsDashboard();
          return;
        }
        let html = '<span style="font-weight:bold;color:#333;margin-right:10px;">Addresses:</span>';
        addrs.forEach((addr) => {
          html += `<span style="display:inline-block;margin:3px 7px 3px 0;padding:6px 12px;background:#f0f0f8;border-radius:7px;box-shadow:0 1px 4px #0001;font-family:monospace;font-size:1.01em;">
          ${addr}
          <a href="#" data-addr="${addr}" class="remove-address" style="color:#e74c3c;margin-left:8px;text-decoration:none;font-weight:bold;font-size:1.15em;">&times;</a>
        </span>`;
        });
        addressListDiv.innerHTML = html;
        messageDiv.innerHTML = "";
        tables.forEach((tbl) => {
          let section = document.getElementById(tbl.section);
          if (section) section.style.display = "";
        });
        // reload tables
        loadPeapodsDashboard();
      }

      addressListDiv.addEventListener("click", function (e) {
        if (e.target && e.target.classList.contains("remove-address")) {
          e.preventDefault();
          let addr = e.target.getAttribute("data-addr");
          let arr = getStoredAddresses();
          arr = arr.filter((a) => a.toLowerCase() !== addr.toLowerCase());
          storeAddresses(arr);
          renderAddressList();
        }
      });

      addForm.addEventListener("submit", function (e) {
        e.preventDefault();
        let addr = addInput.value.trim();
        if (!/^0x[a-fA-F0-9]{40}$/.test(addr)) {
          messageDiv.innerHTML =
            '<span style="color:#e74c3c;">Please enter a valid Ethereum address.</span>';
          return;
        }
        let arr = getStoredAddresses();
        if (arr.some((a) => a.toLowerCase() === addr.toLowerCase())) {
          messageDiv.innerHTML =
            '<span style="color:#e67e22;">Address is already in the list.</span>';
          return;
        }
        arr.push(addr);
        storeAddresses(arr);
        addInput.value = "";
        messageDiv.innerHTML = '<span style="color:#239740;">Address added!</span>';
        setTimeout(() => {
          messageDiv.innerHTML = "";
        }, 1500);
        renderAddressList();
      });

      renderAddressList();
    });

    function updateGrandTotal(totals) {
      let lvf = (totals.collateral || 0) - (totals.borrowed || 0);
      let ptkn = totals.pods || 0;
      let sptkn = totals.spods || 0;
      let lending = totals.lending || 0;
      let total = lvf + ptkn + sptkn + lending;

      document.getElementById("grand-total").textContent =
        "$ " + total.toLocaleString("en-US", { maximumFractionDigits: 2 });
      document.getElementById("lvf-collateral-total").textContent =
        "$ " + lvf.toLocaleString("en-US", { maximumFractionDigits: 2 });
      document.getElementById("ptkn-total").textContent =
        "$ " + ptkn.toLocaleString("en-US", { maximumFractionDigits: 2 });
      document.getElementById("sptkn-total").textContent =
        "$ " + sptkn.toLocaleString("en-US", { maximumFractionDigits: 2 });
      document.getElementById("lending-value-total").textContent =
        "$ " + lending.toLocaleString("en-US", { maximumFractionDigits: 2 });
    };
  </script>
  <div
    style="
      max-width: 1200px;
      margin: 42px auto 32px auto;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 2px 16px #0001;
      padding: 32px 32px 24px;
      text-align: center;
      font-size: 1.22em;
      font-weight: 700;
    "
  >
    <span style="color: #155928; font-size: 1.13em">Grand Total:</span><br />
    <span
      id="grand-total"
      style="font-size: 1.5em; color: #1a8717; font-weight: 900"
      >$ 0.00</span
    ><br />
    <span style="font-size: 0.97em; font-weight: 400">
      LVF Collateral: <span id="lvf-collateral-total" style="color: #333"></span>
      &nbsp;| pTKN Value: <span id="ptkn-total" style="color: #333"></span>
      &nbsp;| spTKN Value: <span id="sptkn-total" style="color: #333"></span>
      &nbsp;| Lending Value: <span id="lending-value-total" style="color: #333"></span>
    </span>
  </div>
</body>
</html>
