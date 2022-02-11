# EU_legislation_reference_querier

This repository allows you to build a network of EU law(s) based on references from and / or to certain EU law(s) (you may also use this for finding court decisions). You select one or more EU law(s) as input, after which all references from and / or to the input laws will be searched. By increasing the source depth and / or target depth, you can increase the degree of separation. For instance, a target depth = 2 means that the references in the input laws to other EU laws will be searched, along with the references in the referred cases. A source depth = 2 entails that the references to the input law(s) will be identified, along with the references to the references that cite the input law(s).

The code can be used to find relevant or applicable EU legislation given a certain input law.

The code is released under a MIT license, but an acknowledgment would be appreciated.
