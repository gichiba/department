# World State Object

## Definition
* A consensus representation of current reality - upstream of outcomes is the world state
* Serves as input to the Values Matrix, with the outcomes contract sitting in-between
* Changes as the state of the world updates - triggering corresponding adjustments in paystreams

## Properties
1. **Consensus-Based**: Requires synced consensus over the state of the world - pretty hard to do with legacy compute
2. **Computationally Intensive**: Mappings in the outcomes contract can be computed directly from an updated world state object, but it's expensive and slow
3. **Verification-Dependent**: Most updating is automated or mechanized in some way, but occasionally certain changes require bespoke manual verification
4. **Infrastructure Legacy**: Idle data centers around the world sit like zombie shopping malls after the quantum crash; they have flops to spare and there's honest money in hosting honest state providers
