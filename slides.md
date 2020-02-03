<!-- .slide: data-background="#2aa198" -->
<!-- .slide: data-state="terminal" -->
# Coda Protocol and zkSNARKs

By
<a href="http://bkase.com">Brandon Kase</a> / <a href="http://twitter.com/bkase_">@bkase_</a>

!!!

### Coda

<img src="img/coda.png" width="50%" />

!!!

### Existing blockchains

<img src="img/1.png" width="100%" />

!!!

### Existing blockchains

<img src="img/2.png" width="100%" />

!!!

### Existing blockchains

<img src="img/3.png" width="100%" />

!!!

### Existing blockchains

<img src="img/4.png" width="100%" />

!!!

### Existing blockchains

<img src="img/5.png" width="100%" />

!!!

### Existing blockchains

<img src="img/6.png" width="100%" />

!!!

### Hard to interact with

<img src="img/other-blockchains.png" width="30%" />

Note: Difficult to use

!!!

### Fewer full nodes

<img src="img/full-nodes-over-time.png" width="100%" />

Note: Risk of centralization

!!!

### Existing networks

Large blockchains make them:

1. Hard to interact with
2. Risk of centralization

!!!

<img src="img/coda-compare.png" width="40%" />

!!!

### Coda

* Stays Decentralized
* <!-- .element: class="fragment" data-fragment-index="1" --> Easy to interact with <!-- .element: class="fragment" data-fragment-index="1" --> <span>=> more useful applications</span> <!-- .element: class="fragment" data-fragment-index="2" -->

Note: Which leads to

!!!

### Coda's Decentralization

* Zero knowledge proofs (specifically zkSNARKs)
* <!-- .element: class="fragment" data-fragment-index="1" --> Inclusive consensus <!-- .element: class="fragment" data-fragment-index="1" -->

!!!

### zk-SNARKs

<span>*Proof* that a computation was run correctly</span> <span>that is *tiny* (~1 kB)</span> <!-- .element: class="fragment" data-fragment-index="1" --> <span>and *easy to check* (&lt;100 ms)</span> <!-- .element: class="fragment" data-fragment-index="2" -->

<span>^^ *Certificate* model</span> <!-- .element: class="fragment" data-fragment-index="3" -->

!!!

### zkSNARKs as certificates

<img src="img/camera.jpg" width="60%" />

Note: Photograph of something as a certificate that this thing exists

!!!

<img src="img/drawing.png" width="100%" />

!!!

<img src="img/drawing-complete.png" width="100%" />

!!!

<img src="img/chain-of-proofs.png" width="100%" />

!!!

<img src="img/comp02.png" width="100%" />

!!!

<img src="img/comp24.png" width="100%" />

!!!

<img src="img/comp04.png" width="100%" />

!!!

### Coda's Decentralization

* Zero knowledge proofs (specifically zkSNARKs)
* *Inclusive consensus*

!!!


### Inclusive Consensus

<img src="img/ouroboros.png" width="50%" />

> https://upload.wikimedia.org/wikipedia/commons/f/fa/Ouroboros.png

Note: Discovered by the folks at IOHK

!!!

### Inclusive Consensus

<img src="img/pie.png" width="80%" />

!!!

### Inclusive Consensus

* No slashing
* <!-- .element: class="fragment" data-fragment-index="1" --> No bonds <!-- .element: class="fragment" data-fragment-index="1" -->
* <!-- .element: class="fragment" data-fragment-index="2" --> No minimum amount to stake <!-- .element: class="fragment" data-fragment-index="2" -->
* <!-- .element: class="fragment" data-fragment-index="3" --> Easy to get started, low risk (because above) <!-- .element: class="fragment" data-fragment-index="3" -->

!!!

### Coda's Decentralization

* Zero knowledge proofs (specifically zkSNARKs)
* Inclusive consensus

!!!

### Coda

* Stays Decentralized
* <!-- .element: class="fragment" data-fragment-index="1" --> *Easy to interact with* <!-- .element: class="fragment" data-fragment-index="1" --> <span>=> more useful applications</span> <!-- .element: class="fragment" data-fragment-index="1" -->

Note: Which leads to

!!!

### Coda Usability

We are investing heavily in *user experience* for node operators and developers

!!!

### Coda Everywhere

<img src="img/coda-everywhere.png" width="70%" />

Note: Non-consensus node; unlike a light-node in other networks, does fully verify the state (as easy as checking a snark); no need to delegate trust

!!!

### Coda in the browser

<img src="img/internet-explorer.png" width="50%" />

!!!

### Coda

* Stays Decentralized
* Easy to interact with <span> *=> more useful applications* </span> <!-- .element: class="fragment" data-fragment-index="1" -->

!!!

### Coda Applications

Coda is early in development <span>custom tokens, tokenized assets, games</span> <!-- .element: class="fragment" data-fragment-index="1" -->

!!!

### Coda Applications

And *zksnark apps*

!!!

### zk-SNARKs

<span>*Proof* that a computation was run correctly</span> <span>that is *tiny* (~1 kB)</span> <!-- .element: class="fragment" data-fragment-index="1" --> <span>and *easy to check* (&lt;100 ms)</span> <!-- .element: class="fragment" data-fragment-index="2" -->

<span>^^ *Certificate* model</span> <!-- .element: class="fragment" data-fragment-index="3" -->

!!!

### zkSNARKs

<span>*Proof*</span> <span>that there exists secret data</span><!-- .element: class="fragment" data-fragment-index="1" --><span> that I know,</span><!-- .element: class="fragment" data-fragment-index="2" --><span> such that some *predicate* holds on the data</span><!-- .element: class="fragment" data-fragment-index="3" -->

<span>^^ *Hiding* model</span><!-- .element: class="fragment" data-fragment-index="4" -->

!!!

### zkSNARK statements

<span> _There exists_ data</span><span> _such that_ predicates hold on that data</span><!-- .element: class="fragment" data-fragment-index="1" -->

Note: There exists DATA s.t. PROPERTY

!!!

### zkSNARK statements

<span> _There exists_ some number x</span><span> _such that_ x^2 = 9</span><!-- .element: class="fragment" data-fragment-index="1" -->

!!!

### Coda zkSNARK Application

<span> _There exists_ several bank accounts and real estate assets my business owns,</span> <span> _such that_ the sum of the accounts is above 10billion won</span><!-- .element: class="fragment" data-fragment-index="1" --> <span>therefore please give me a good interest rate on this business loan</span><!-- .element: class="fragment" data-fragment-index="2" -->

<span>Your private information *remains* private</span><!-- .element: class="fragment" data-fragment-index="3" -->

!!!

### Coda

* Stays Decentralized
* Easy to interact with <span> => more useful applications </span>

!!!

### Genesis program

<img src="img/genesis.png" width="100%" />

!!!

### Genesis Program

https://codaprotocol.com/genesis

* Help us strengthen Coda Protocol
* <!-- .element: class="fragment" data-fragment-index="1" --> Genesis members will receive a distribution of *66,000 tokens* at launch <!-- .element: class="fragment" data-fragment-index="1" -->
* <!-- .element: class="fragment" data-fragment-index="2" --> *1000 members* will be selected <!-- .element: class="fragment" data-fragment-index="2" -->
* <!-- .element: class="fragment" data-fragment-index="3" --> At mainnet launch, *6.6% of the protocol will be distributed* in this manner <!-- .element: class="fragment" data-fragment-index="3" -->
* <!-- .element: class="fragment" data-fragment-index="4" --> To learn more see the Terms and Conditions on the genesis page <!-- .element: class="fragment" data-fragment-index="4" -->

!!!

<!-- .slide: data-background="#2aa198" -->
<!-- .slide: data-state="terminal" -->
# Thanks

* Community: <a href=https://bit.ly/CodaDiscord>bit.ly/CodaDiscord</a>
* Follow our progress: <a href="https://twitter.com/codaprotocol">@CodaProtocol</a>
* Website: <a href="https://codaprotocol.com">codaprotocol.com</a>
* Genesis Program: <a href="https://codaprotocol.com/genesis">codaprotocol.com/genesis</a>

By
<a href="http://bkase.com">Brandon Kase</a> / <a href="http://twitter.com/bkase_">@bkase_</a>

