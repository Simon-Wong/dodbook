# Summary

* [Intro](intro.md)
* [Data-Oriented Design](data-oriented.md)
    * [All About Data](sub-dod/allaboutdata.md)
    * [The Problem Domain](sub-dod/notproblem.md)
    * [Data and Statistics](sub-dod/dataandstats.md)
    * [Data Changes](sub-dod/datachanges.md)
    * [How is Data Formed](sub-dod/dataform.md)
    * [Providing a Computational Framework](sub-dod/comp.md)
* [Existence Based Processing](exist.md)
    * [Why use an if](sub-exist/if.md)
    * [Dont use bools](sub-exist/bool.md)
    * [Dont use enums](sub-exist/enum.md)
    * [Prelude to polymorphism](sub-exist/poly.md)
    * [Dynamic runtime polymorphism](sub-exist/dynamic.md)
    * [Event handling](sub-exist/events.md)
* [Component Oriented Development](component.md)
    * [Components in the wild](sub-component/wild.md)
    * [Away from the Hierarchy](sub-component/awayfromhier.md)
    * [Towards Managers](sub-component/managers.md)
    * [There is no Entity](sub-component/noentity.md)
* [Hierarchical Level of Detail](hier.md)
	 * [Existence from null to infinity](sub-hier/exist-range.md)
	 * [Mementos](sub-hier/mementos.md)
	 * [JIT data generation](sub-hier/JIT.md)
	 * [Alternative Axes](sub-hier/alt-axes.md)
* [Conditional Flow](condition.md)
	 * [Building Questions](sub-condition/questions.md)
	 * [Flip it on its head](sub-condition/flip.md)
	 * [Logging decisions for debug](sub-condition/logging.md)
	 * [Branching without branching](sub-condition/branching.md)
* [Finite State Machines](fsm.md)
	 * [Tables as states](sub-fsm/tables.md)
	 * [Implementing transitions](sub-fsm/transitions.md)
	 * [Condition tables as triggers](sub-fsm/triggers.md)
	 * [Conditions as events](sub-fsm/events.md)
* [Searching](search.md)
	 * [Indexes](sub-search/indexes.md)
	 * [A data-oriented lookup](sub-search/lookup.md)
	 * [Finding lowest or highest is a sorting problem](sub-search/hilow.md)
	 * [Finding random is a hash/tree issue](sub-search/hash.md)
* [Sorting](sort.md)
	 * [Do you need to?](sub-sort/need.md)
	 * [Maintain by insertion sort or parallel merge sort](sub-sort/maintain.md)
	 * [Sorting for your platfom](sub-sort/platform.md)
* [An Entity Relational Approach](RDB.md)
	 * [How does relational data differ?](sub-RDB/relational.md)
	 * [Normalisation](sub-RDB/normalisation.md)
	 * [Implicit Entities](sub-RDB/implicit.md)
	 * [Components imply entities](sub-RDB/components.md)
	 * [Cosmic Hierarchies](sub-RDB/cosmic.md)
	 * [Structs of Arrays](sub-RDB/structsofarrays.md)
	 * [Stream Processing](sub-RDB/stream.md)
	 * [Beautiful Homogeneity](sub-RDB/beautiful.md)
* [Optimisation](optim.md)
	 * [Tables](sub-optim/tables.md)
	 * [Transforms](sub-optim/transforms.md)
	 * [Spatial sets for collisions](sub-optim/spatial.md)
	 * [Lazy Evaluation for the masses](sub-optim/lazy.md)
	 * [Not getting what you didn’t ask for](sub-optim/notgetting.md)
	 * [Varying Length Sets](sub-optim/varyinglength.md)
	 * [Bit twiddling decision tables](sub-optim/bittwiddling.md)
	 * [Data driven techniques](sub-optim/datadriven.md)
* [Concurrency](conc.md)
	 * [What it means to be thread-safe](sub-conc/threadsafe.md)
	 * [Inherently concurrent operations](sub-conc/inherent.md)
	 * [Queues as gateways, and “Now”](sub-conc/gateways.md)
* [Examples](example.md)
	 * [Data-manipulation](sub-example/manipulation.md)
	 * [Game entities](sub-example/entities.md)
* [Maintenance and Other Real World Issues](maintenance.md)
	 * [Debugging](sub-maint/debug.md)
	 * [Reusability](sub-maint/reuse.md)
	 * [Unit Testing](sub-maint/testing.md)
	 * [Refactoring](sub-maint/refactor.md)
* [Design Patterns](patterns.md)
	 * [Data-Oriented Design Patterns](sub-patterns/dodpat.md)
	 * [Existing design patterns](sub-patterns/ooppat.md)
	 * [Locking out anti-patterns](sub-patterns/antipat.md)
* [What's The Harm In Object-Oriented Design?](harm.md)
	 * [The Harm](sub-harm/harm.md)
	 * [Mapping the problem](sub-harm/mapping.md)
	 * [Internalised state](sub-harm/stateful.md)
	 * [Hierarchical design](sub-harm/inheritance.md)
	 * [Divions of labour](sub-harm/modules.md)
	 * [Reusable generic code](sub-harm/reuse.md)
* [Hardware - Hopes, Dreams, and History](hardware.md)
	 * [Sequential data](sub-hardware/sequential.md)
	 * [Deep Pipes](sub-hardware/pipelines.md)
	 * [Microcode: virtually function calls.](sub-hardware/microcode.md)
	 * [Single Instruction Multiple Data](sub-hardware/simd.md)
	 * [Predictable instructions](sub-hardware/predictable.md)
* [Concerns For The Future](future.md)
	 * [Parallel Processing](sub-future/parallel.md)
	 * [Concurrent Design](sub-future/concurrent.md)
	 * [Distributed computing](sub-future/distributed.md)
	 * [Runtime hardware configuration](sub-future/runtimehardware.md)
	 * [Data centric development in hardware design](sub-future/hardwaredesign.md)
* [Count](count.md)
	 * [Learning to count](sub-count/learn.md)
	 * [Counting to find out facts](sub-count/facts.md)
	 * [Domain Knowledge](sub-count/domain.md)
	 * [Discovering facts from counting](sub-count/discover.md)

