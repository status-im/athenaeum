# The Ethereum Athenæum

## What will you find ?

A JSON file and hopefully in the future some visualization that keep track of Ethereum research and help everyone make sense of the exploding number of directions being followed simultaneously.

The JSON file currently contains:

- A **key** being a research direction like Sharding, Plasma, RANDAO, Casper FFG, Casper CBC, ...
- A **summary**, one-liner to describe the feature
- A **description**, with more in-depth explanation. Note that many are in draft or state of flux, make sure to check the date.
- A **improves** field. Taxonomy currently is `throughput`, `transaction cost`, `latency`, `decentralization`.
- A **worsen** field. Same taxonomy.
- A **layer** field. To track research that will necessitate a hard fork (layer 1), and research that can be build on top of the core (as a smart contract).
- A **tags** field. As we dive into the low-level detail, tags will be useful to group semantically. Taxonomy currently is `sharding`, `architecture`, `cryptography`, `random number generator`, `proof of stake`, `networking`, `protocol`, `library`
- A **comments** field
- A **resources** field which links to explanatory blog posts, videos, specifications and if specs is in flux, discussions.
- A **status** field to track the state of the research: **research**, **draft**, **proof-of-concept**, **implemented**
- A **last_update** field. Research is moving fast and scope can expand, shrink or completely disappear from week to week. Be sure to check the date.
- An **implementation** field. Track the implementations.
- A **dependencies** field.
- A **required_by** field.

## Target audience

The main audience of this JSON are client developers. Consequently, very low-level building blocks will be part of the JSON (for example the BLS12-381 signature). This will facilitate splitting work in a client team and track progress.

Implementation "details". Regarding implementation of low-level blocks (for example cryptography), there will be a heavy focus on libraries that can be used with [Nimbus](https://github.com/status-im/nimbus)

## What's in a name?

In ancient Athens, the athenæum was a place where rhetorician, orators and philosophers gathered.
By extension, an athenaeum became a gathering of scholars.

Emperor Hadrian built the Athenæum in ancient Rome, a school of high reputation for literary and scientific study.

Nowadays, the name is used for libraries, cultural centers, museums, high school (Belgium) or university (Netherlands).
