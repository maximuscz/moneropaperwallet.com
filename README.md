<h1><strong>Why use a Monero paper wallet?</strong></h1>
<p>Let’s look at a simple and free method to keep your valuable Monero safe.</p>
<p>The paper wallet is ideal for long-term cold storage. It can also make a great gift. If you want to protect your Monero while still having relatively easy access to it, a Ledger Wallet will be the best option once available (still under development).</p>
<p>In any case, it is highly discouraged to leave your cryptocurrencies on exchanges or online wallets, as they are frequent targets of hackers. A paper wallet keeps your private keys (mnemonic seed) offline. By storing your crypto on a physical medium, it becomes nearly tamper-proof and your exposure to hackers or third parties is greatly reduced.</p>
<p><strong>Important:</strong> Make at least two copies of your paper wallet and store them in different secure places — for instance, one in a safe deposit box at a bank (if you trust it) and another hidden safely at home. This way, if something happens such as a fire, you’ll still have a backup of your private keys. It’s also wise to physically protect the paper wallet, for example by sealing it in a small plastic bag.</p>
<p>There are several paper wallet generators available online. For this tutorial, we’ll use a minimal English-only version. If you wish to generate a mnemonic seed in another language, you’ll need to use a different generator.</p>
<ul>
  <li>Minimal version (English only): <a href="http://moneropaperwallet.com" target="_blank">moneropaperwallet.com</a></li>
</ul>

<h1><strong>How to create a Monero paper wallet</strong></h1>
<p>When you create a paper wallet, you’ll receive a 25-word mnemonic seed. <strong>This is the most important part of your wallet.</strong> With this 25-word seed, you can regenerate your private keys and access your funds anytime.</p>
<p>For the screenshots below, I used <a href="http://moneropaperwallet.com" target="_blank">moneropaperwallet.com</a>:</p>
<ol>
  <li>Your public address (used to receive funds)</li>
  <li>Your mnemonic seed (<strong>Write it down and store it safely!</strong>)</li>
  <li>Your spend and view keys</li>
</ol>
<p><a href="https://i.imgur.com/k5gpPZq.jpg" target="_blank"><img src="https://i.imgur.com/k5gpPZq.jpg"></a></p>
<p>As mentioned earlier, make at least two copies! If you lose your mnemonic seed, you’ll permanently lose access to your funds.</p>
<p><strong>Tip:</strong> Write the creation date on your paper wallet — it’s useful if you ever need to restore your wallet without scanning the entire blockchain.</p>

<h1><strong>How to restore a Monero paper wallet</strong></h1>
<p>The first step is to start the daemon and let it synchronize with the network.</p>
<p>Download the Monero CLI (command-line interface) from the official website: <a href="https://getmonero.org/downloads/" target="_blank" rel="nofollow noopener" title="This link will take you away from steemit.com" class="postImage postLink">https://getmonero.org/downloads/</a></p>
<p>In the Monero directory, double-click <strong>monerod.exe</strong>. The daemon will begin syncing with the network — this may take quite some time depending on your computer and disk speed. Once synchronization is complete, you’ll see a “SYNCHRONIZED OK” message like the example below:</p>
<p><a href="https://i.imgur.com/S1Ao2CT.jpg"><img src="https://i.imgur.com/S1Ao2CT.jpg"></a></p>

<p>The next step is to restore your wallet using your mnemonic seed.</p>
<p>Open a Windows command prompt and enter the following command:</p>
<p><strong>monero-wallet-cli.exe --restore-deterministic-wallet</strong></p>
<p><a href="https://i.imgur.com/hQJunft.jpg"><img src="https://i.imgur.com/hQJunft.jpg"></a></p>

<p>Then follow these steps:</p>
<ol>
  <li>Enter a wallet name</li>
  <li>Type in your 25-word mnemonic seed</li>
  <li>Set a password</li>
  <li>Specify whether to scan from a certain date (YYYY-MM-DD) or start from 0</li>
</ol>
<p><a href="https://i.imgur.com/fyUlsfn.jpg"><img src="https://i.imgur.com/fyUlsfn.jpg"></a></p>
<p>Your wallet will resync, and once complete, you’ll be ready to spend your Monero!</p>
<p>Please leave a comment if you found this tutorial helpful!</p>
