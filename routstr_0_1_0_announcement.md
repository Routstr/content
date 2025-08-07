# Announcing Routstr Core v0.1.0: Come Run Routstr Nodes with Us
# -- SHORT FORM --

With this stable release, anyone can run Routstr nodes and help decentralize AI access to anyone, anywhere on earth!

Come run a Routstr node and serve models from OpenAI, Anthropic, x-ai, Google, Replicate, or OpenRouter (charges 5% extra) to anyone on the open internet and earn Bitcoin via Cashu/Lightning. 

With v0.1.0, we made Routstr incredibly stable, but this is still a Beta version. If you come across a problem, we’d appreciate it if you report the bug to us on our Github. 

Along with making Routstr more robust, we added these new features to Routstr: 
1. **Multiple Cashu Mint Support:** Users and nodes don’t need to use the same mint)
2. **Multi-Currency Support:** Sat and msats are both supported right now)
3. **Pay per Request with X-Cashu Headers:** Send a Cashu token with enough balance and get the change back along with the response)
4. **Admin Dashboard and Withdrawals:** A simple dashboard to look your and your users’ balances, more updates coming)

Links and more: 👇️ 

# -- LONG FORM -- 
## Links: 
- Try Routstr using our chat app: https://chat.routstr.com
- Roustr Core (To run a node): https://github.com/Routstr/routstr-core
- Other Routstr clients: https://github.com/Routstr

# A Message: 
Four months ago, we asked, “What would AI look like if no company, country or credit-card could gate-keep it?”

We wanted to build the infrastructure for permissionless AI. After 4 months, we are proud to announce Roustr Beta v0.1.0 as a stable version that we are comfortable with releasing for anyone to run a Routstr Node. You might be wondering why are we making this decentralized with nodes and other jargon. We feel the obligation to answer why. 

## Why Routstr? 
OpenRouter exists, doesn’t it? Yes, but are we gonna rely on another centralized service again for one of the most important technology of this century? 

Routstr is important for two main reasons: 
1. **Permissionless Listing:** Routstr allows anyone who has GPU compute to start a Routstr node and start serving AI inference to anyone who needs it. 
2. **Permissionless Access:** It also enables anyone out there without an email or a known IP address to pay with Bitcoin and access AI. 

## Leveraging Nostr
### Discovery
Routstr leverages the permissionlessness nature of Nostr to help anyone with access to AI to serve anyone that needs it. We do this by broadcasting a Nostr event to various Nostr relays which can then be fetched by any client (like our chat app) to discover nodes offering AI inference at various prices. 

### Gossiping
Various Routstr clients that use pseudonymous Routstr nodes for AI inference can gossip on the Nostr network to ensure that Routstr nodes don’t just steal from them. They can report mispricing, serving lower quality models as higher quality ones, or just not returning a response for a Cashu token. This is in contrast with the anonymity of Bitcoin nodes because the truth is derived from a chain of blocks, but Routstr must operate on some pseudonymous trust for it to work. 

### Sovereignty
None of the chat app, the node or any other software we build rely on a centralized server to operate. They all rely on Nostr relays for application state storage (nip-44), Cashu balance storage (nip-60) and for relay/mint selection. There is no way Routstr team or anyone can rug any user as users have full sovereignty. 

## Help Us!
There are a few ways you can help us. 

### Spread the word!
We need more Routstr nodes. And more Routstr users that our nodes can serve. Help us reach them both. 

### Run a node and give us feedback
Consider running a node by simply cloning our Routstr Core repo and setting up Ngrok or by setting up a subdomain. 

### Contribute to our code
If you are dev, we would highly appreciate your code contributions. Bonus points if you use Routstr to improve Routstr :). 

Built with Love! 

Routstr, A Freedom AI Tech Protocol
