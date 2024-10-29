# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Finding a server's BMC / IPMI IP address with ipmitool
 - [https://www.jeffgeerling.com/blog/2024/finding-servers-bmc-ipmi-ip-address-ipmitool](https://www.jeffgeerling.com/blog/2024/finding-servers-bmc-ipmi-ip-address-ipmitool)
 - RSS feed: $source
 - date published: 2024-10-28T16:17:02+00:00

<span class="field field--name-title field--type-string field--label-hidden">Finding a server's BMC / IPMI IP address with ipmitool</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>I test servers on a temporary basis a lot, and many enterprise servers don't have as user-friendly external port indications, or little OLED displays to provide useful information. They're no-frills because they don't need frills, you just deploy them and they run for years.</p>

<p>I often need to gain access to the server's IPMI/BMC interface to manage the server remotely, and it's not always obvious what IP address is assigned if you don't manually assign one via your router and a MAC address.</p>

<p>I could scan my network for the IP address, but assuming I have the server booted and it's a modern Supermicro or other standard system, I can use <code>ipmitool</code> to grab the BMC IP:</p></div>
      <span 

