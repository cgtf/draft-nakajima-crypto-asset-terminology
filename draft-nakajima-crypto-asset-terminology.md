---
title: Terminology for Crypto Asset
abbrev: Crypto Asset Terminology
docname: draft-nakajima-crypto-asset-terminology-latest
category: info

ipr: trust200902
area: General
workgroup:
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
-
   ins: H. Nakajima
   name: Hirotaka Nakajima
   organization: Mercari, Inc. R4D
   abbrev: Mercari R4D
   street:
   - Roppongi Hills Mori Tower 18F
   - 6-10-1 Roppongi
   city: Minato, Tokyo
   code: '106-6118'
   country: JAPAN
   email: nunnun@mercari.com
-
   ins: M. Kusunoki
   name: Masanori Kusunoki
   organization: Japan Digital Design, Inc.
   abbrev: JDD
-
   ins: K. Hida
   name: Keiichi Hida
   organization: Japan Blockchain Association
   abbrev: JBA
-
  ins: Y. Suga
  name: Yuji Suga
  organization: Advanced Security Division, Internet Initiative Japan Inc.
  abbrev: Advanced Security Div, IIJ
  street:
  - Iidabashi Grand Bloom,
  - 2-10-2 Fujimi
  city: Chiyoda, Tokyo
  code: '102-0071'
  country: JAPAN
  email: suga@iij.ad.jp

normative:
  RFC2119:

informative:
  RFC4949:
  MasteringBitcoinOnline:
    title: "Mastering Bitcoin"
    author:
    - name: "Andreas M."
    date: 2018/03/15
    target: https://github.com/bitcoinbook/bitcoinbook

--- abstract

This document provides terminology used in crypto asset.

--- middle

# Introduction

Our goal with this document is to improve our understanding on a set of terms which frequently used in documents which related to crypto asset.
Mutual understanding about terminology may help to reach a consensus on issues we're trying to solve.

# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.

# Terms and Definitions

address:
: An identifier to represent a public key in a blockchain network.

asymmetric cryptography:
: Defined in {{RFC4949}} as "A modern branch of cryptography (popularly known as
  "public-key cryptography") in which the algorithms use a pair of keys (a
    public key and a private key) and use a different component of the pair
    for each of two counterpart cryptographic operations
    (e.g., encryption and decryption, or signature creation and signature verification). "

block:
: A set of transactions on a blockchain which contains a cryptographic hash value of previous block.

blockchain:
: TBD
<!-- : One of a method of distributed ledgers which confirms  -->

confirmation:
: TBD

consensus:
: TBD

consortium chain:
: TBD

crypto assets:
: TBD

deterministric wallet:
: See: wallet

digital signature:
: Defined in {{RFC4949}} as "A value computed with a cryptographic algorithm and
associated with a data object in such a way that any recipient of
the data can use the signature to verify the data's origin and
integrity."

distributed ledger:
: TBD

double spending:
: Defined in {{MasteringBitcoinOnline}} as "result of successfully spending some money more than once."

fiat money:
: Currency which has been established by government or other authorities.

fork:
: Defined in {{MasteringBitcoinOnline}} as "Fork, also known as accidental fork, occurs when two or more blocks have the same block height, forking the block chain. Typically occurs when two or more miners find blocks at nearly the same time."

genesis block:
: An initial block on a blockchain. Genesis block may differ to distinguish chains.

hard fork:
: See: fork

hash value:
: Defined in {{RFC4949}} as "The output of a hash function.".

hash rate:
: Amount of a hash value which node is able to generate per unit of time (generally per second)

hierarchy deterministic wallet:
: See: wallet

mainchain:
: TBD

mining:
: A process to append a received transaction to a block by validating a transaction with agreed consensus rules such as proof-of-work and proof-of-stake. Miner is a network node which contributes its resources to mining.

miner:
: See: mining

multisignature:
: Defined in {{MasteringBitcoinOnline}} as "requiring more than one key to authorize a bitcoin transaction". In this scope, transaction is not limited to bitcoin transaction.

node:
: TBD

off-chain:
: TBD

on-chain:
: TBD

orphan block:
: Defined in {{MasteringBitcoinOnline}} as "Blocks whose parent block has not been processed by the local node, so they can’t be fully validated yet."

permissioned chain:
: TBD

permissionless chain:
: See: permissioned chain

public chain:
: TBD

public key:
: Defined in {{RFC4949}} as "The publicly disclosable component of a pair of
      cryptographic keys used for asymmetric cryptography."

private chain:
: TBD

private key:
: Defined in {{RFC4949}} as "The secret component of a pair of cryptographic keys used
      for asymmetric cryptography."

proof of importance:
: TBD

proof-of-stake:
: Defined in {{MasteringBitcoinOnline}} as "method by which a cryptocurrency blockchain network aims to achieve distributed consensus."

proof-of-work:
: Defined in {{MasteringBitcoinOnline}} as "A piece of data that requires significant computation to find."

reorganization:
: TBD

reward:
: Value by the blockchain network which assigned to a miner who successfully validates a transaction. Rules may differ among blockchains and consensus rules.

sidechain:
: see off-chain

smart contract:
: TBD

soft fork:
: See: fork

subchain:
: TBD

token:
: TBD

transaction:
: Defined in {{MasteringBitcoinOnline}} as "More precisely, a transaction is a signed data structure expressing a transfer of value."

validation:
: TBD

validated:
: See: validation

validator:
: See: validation

wallet:
: A set of key pair composed of public key and private key.

# Security Considerations

This document defines terminology for crypto asset. Therefore, there is no security considerations.

# IANA Considerations

None.

--- back

# Acknowledgments
{:numbered="false"}

To be filled
