# Hackintosh-Dell-3443-OpenCore

# Hardware

<table>
<thead>
  <tr>
    <th>Components</th>
    <th>Recommended</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Motherboard</td>
    <td></td>
  </tr>
  <tr>
    <td>CPU</td>
    <td><a href="https://ark.intel.com/content/www/us/en/ark/products/85214/intel-core-i7-5500u-processor-4m-cache-up-to-3-00-ghz.html" target="_blank" rel="noopener noreferrer">Intel® Core™ i7-5500U Processor</a></td>
  </tr>
  <tr>
    <td>Ram</td>
    <td>Hynix 8GB DDR3 Bus 1600MHz</td>
  </tr>
  <tr>
    <td>Graphics Card</td>
    <td>Intel® HD Graphics 5500<br><a href="https://www.nvidia.com/en-us/geforce/gaming-laptops/geforce-840m/" target="_blank" rel="noopener noreferrer">Nvidia GeForce GT 840M 2GB</a><br></td>
  </tr>
  <tr>
    <td>WiFi</td>
    <td>DW1707 &lt;=&gt; AR9565</td>
  </tr>
  <tr>
    <td>BIOS</td>
    <td><a href="https://www.dell.com/support/home/en-vn/product-support/product/inspiron-14-3443-laptop/drivers" target="_blank" rel="noopener noreferrer">A13</a></td>
  </tr>
  <tr>
    <td>OpenCore</td>
    <td><a href="https://github.com/acidanthera/OpenCorePkg/releases" target="_blank" rel="noopener noreferrer">0.6.7</a></td>
  </tr>
  <tr>
    <td>macOS</td>
    <td>11.2.3</td>
  </tr>
</tbody>
</table>

# Important!

YOU MUST modify SN/UUID/MLB/ROM values in config.plist file. ROM value is the MAC address of your motherboard built-in network card, check it on BIOS settings.

# Status

Working

- [x] QE/CI
- [x] Restart, Sleep and Shutdown
- [x] CPU Power Management
- [x] Ethernet Realtek RTL8100
- [x] Audio Jack (Realtek ALC 255)
- [x] Wifi
- [x] HDMI Audio
- [x] iMessage, Facetime
- [x] All Port USB 2.0 and USB 3.0
 
Not working at the moment

- [ ] AirDrop
- [ ] Handoff
- [ ] Sidecar
- [ ] Trackpad
- [ ] dGPU (Disabled)

Not tested
  
# Screenshot

