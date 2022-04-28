# Metadata 
## requirements
* simple
* composable
* searcharble SAFE 
* human and machine readable

## job 
* verbose - Biocompute object
    * object information ~ molecule ipnft toplevel
    * properties
        * research lead
        * provenance domain - laboratory
            * wallets server
        * 
    * environment domain
    * input
        * uri
    * output
        * uri to 
    * object_information
* exisitng - Molecule IP-NFT standard 
https://pfamwznmskrsyin62vzewfwros4jvltf5rnwm3xgoqytesyvomrq.arweave.net/eUDLZaySoywhvtVySxbRdLiarmXsW2Zu5nQxMksVcyM
https://vbvqpfwvgq6tprsnenpwekslljyxatroudyqeuomttqrim5cum.arweave.net/qGsHltU0PTfGTSNfYipLWnFwTi6g8Q-JRzJzhFDOio4

* compatible - opensea ERC721 (https://docs.opensea.io/docs/metadata-standards)




* composability
* optimized for search

* take inspiration from bio-compute object 
* transformable
    * opensea
    * etc.

## Molecule IP-NFT toplevel 

````
{
  "name": "The Longevity Molecule (IPNFT)",
  "description": "The Scheibye-Knudsen lab has analyzed 1.5 billion prescriptions from 4.8 million individuals over 40 years in The Danish National Health Service Prescription Database and correlated this with the survival of individuals prescribed certain drugs. The Scheibye-Knudsen Lab has identified several FDA-approved medications that appear to have a strong effect on lifespan following analysis. This project focuses on testing and developing three of these small molecules as possible interventions in aging, with the first series of experiments testing these therapies in fruit flies and human cells. This is an exclusive license agreement for the IP resulting from these experiments.",
  "image": "https://arweave.net/gQm_NpkJIjEFD6sOVHLEJ-tZIKhRvgmYEl5es0g-YdQ",
  "properties": {
    "agreement_type": "Trade Secret",
    "industry": "Pharmaceutical R&D",
    "research_lead": "The Scheibye-Knudsen Lab"
    "refernces_1": lab_token1_uri
    "references_2": lab_token2_uri
  }
}
````

## lab_token1_uri .json

````
name: openlab reversecomplement 
description: user-defined description 
"image": 

````

resolve ENS on the user interface 
but do not reference ENS in metadata ever

````
{
    "name": "openlab reverse complement",
    "description": "the reverse complement to an input DNA sequence",
    "image": "https://ipfs.io/ipfs/QmZ9oReVUiNQSc9GaqqTEPUW3XHo6eprVSa9nqbGNotP8B",
    "attributes": [
        {
            "trait_type": "Service ID",
            "value": "0"
        },
        {
            "trait_type": "Service Name",
            "value": "lab-reverse_complement"
        },
        {
            "trait_type": "Input Sequence",
            "value": "ctatataaataaataaataaatattatatatatag"
        },
        {
            "trait_type": "Output Sequence",
            "value": "ctatatatataatatttatttatttatttatatag"
        },
        {
            "trait_type": "Metadata",
            "value": {
                "repository": "https://github.com/openlab-apps/lab-reverse_complement/tree/2-serverless-stage",
                "commit": "ddf80e0e953fde3d8cbe9f17fc3f1108cac7bc37",
                "deployment": "https://02wun6.deta.dev/"
            }
        },
        {
            "trait_type": "Job URI",
            "value": "ipfs://QmdQP9D44Hgp8697FpGJrkTiQYSiUH3xEsvumKX3jJmV58"
        }
    ]
}
````

## Encryption 


