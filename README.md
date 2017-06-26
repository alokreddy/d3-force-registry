# d3-force-registry
A curated compilation of plugins and all-things related to [d3-force](https://github.com/d3/d3-force).

## Force Plugins

| Plugin | Code | Description | Examples |
|---|---|---|---|
| d3.bboxCollide | [d3-bboxCollide](https://github.com/emeeks/d3-bboxCollide) | Repelling force that prevents rectangular nodes from overlapping with each other. Great for avoiding label overlaps. | [Guitar hero](https://bl.ocks.org/emeeks/b562c2c449ee30ec577f2d8339b2ce1c), [Word clouds](https://bl.ocks.org/emeeks/19a1d77fc6ad812faedb648218b7ad60) |
| d3.forceAttract | [d3-force-attract](https://github.com/ericsoco/d3-force-attract) | Spring-like force to attract nodes to a particular *<x,y>* point.| [Mouse following](https://bl.ocks.org/ericsoco/7eebab15da4bb1040977da508aebbff6), [Multiple with collision](https://bl.ocks.org/ericsoco/6e0573860e7f6655cee885d8b1b84065) |
| d3.forceBounce | [d3-force-bounce](https://github.com/vasturiano/d3-force-bounce) | Elastic collision force between nodes. Useful to simulate natural collisions between circular objects that conserve energy and momentum. | [Newton's cradle](https://bl.ocks.org/vasturiano/0a05e58d5122cde888793c374d587aac), [Entropy](https://bl.ocks.org/vasturiano/2992bcb530bc2d64519c5b25201492fd), [Brownian motion](https://bl.ocks.org/mikeskaug/27de9c33d44d6b415b2c7b3e7362cde8) |
| d3.forceCenter | [d3-force](https://github.com/d3/d3-force#centering) (core) | Translate all nodes as a group towards the center of the canvas. Manipulates nodes coordinates directly, instead of their velocity. | [Force-directed graph](https://bl.ocks.org/mbostock/f584aa36df54c451c94a9d0798caed35) |
| d3.forceCluster | [d3-force-cluster](https://github.com/ericsoco/d3-force-cluster) | Spring-like force to attract nodes towards a set of cluster focus points. | [Cluster layout](https://bl.ocks.org/ericsoco/4e1b7b628771ae77753842e6dabfcef3), [Clustered attraction](https://bl.ocks.org/ericsoco/d2d49d95d2f75552ac64f0125440b35e) |
| d3.forceCollide | [d3-force](https://github.com/d3/d3-force#collision) (core) | Repelling force that prevents circular nodes from overlapping with each other. | [Collision detection](https://bl.ocks.org/mbostock/3231298), [Venn](https://bl.ocks.org/emeeks/6a77dbcf149b4b9e772b30af71d11b06), [Hamilton characters](https://bl.ocks.org/sxywu/570df88e66e420191d33dc5b5650aaf4) |
| d3.forceContainer | [d3-force-container](https://github.com/1wheel/d3-force-container) | Constrain nodes to a bounding box. | [Faces](https://bl.ocks.org/1wheel/68073eeba4d19c454a8c25fcd6e9e68a) |
| d3.forceLink | [d3-force](https://github.com/d3/d3-force#links) (core) | Spring-like attraction/repulsion force applied to node-pairs. | [Force-directed tree](https://bl.ocks.org/mbostock/95aa92e2f4e8345aaa55a4a94d41ce37), [Cloth](https://bl.ocks.org/mbostock/1b64ec067fcfc51e7471d944f51f1611) |
| d3.forceMagnetic | [d3-force-magnetic](https://github.com/vasturiano/d3-force-magnetic) | Inverse-square (with distance) attraction/repulsion force applied to all nodes or dedicated node-pairs edges. Useful to simulate natural occurring forces such as gravity or electrostatic. | [Accretion](https://bl.ocks.org/vasturiano/27fbd16d7e9131fbc8e8e93113f9896c), [Orbits](https://bl.ocks.org/vasturiano/5086628299fa6c1bae0094f93d112634) |
| d3.forceManyBody | [d3-force](https://github.com/d3/d3-force#many-body) (core) | Inverse-linear (with distance) attraction/repulsion force applied to all nodes. Typically used as node repulsion in force-directed graphs for distributed spread. | [Blocks graph](http://bl.ocks.org/mbostock/afecf1ce04644ad9036ca146d2084895), [Force simulation](https://bl.ocks.org/HarryStevens/f636199a46fc4b210fbca3b1dc4ef372) |
| d3.forceSurface | [d3-force-surface](https://github.com/vasturiano/d3-force-surface) | Bounce nodes off a set of line-segment surfaces. Surface contact triggers an elastic collision obbeying the surface angle. | [Pong](https://bl.ocks.org/vasturiano/94107e18d438942f92b217809eb3e7ba), [Particle container](https://bl.ocks.org/vasturiano/2992bcb530bc2d64519c5b25201492fd) |
| d3.forceX | [d3-force](https://github.com/d3/d3-force#forceX) (core) | Horizontal spring-like attraction force. | [Beeswarm](https://bl.ocks.org/mbostock/6526445e2b44303eebf21da3b6627320) |
| d3.forceY | [d3-force](https://github.com/d3/d3-force#forceY) (core) | Vertical spring-like attraction force. | [Vertical beeswarm](https://bl.ocks.org/jonsadka/ad1a3698615485a310f9228ed7ea93cd) |
| d3.forceZ | [d3-force-3d](https://github.com/vasturiano/d3-force-3d#forcez) | Spring-like attraction force in the Z dimension for 3D representations. | - |

## Modules

| Name | Code | Description | Example |
|---|---|---|---|
| d3-force-3d | [d3-force-3d](https://github.com/vasturiano/d3-force-3d) | Extended version of d3-force to run simulations in 3D or 1D. | [Multi-dimensional force simulation](https://bl.ocks.org/vasturiano/f59675656258d3f490e9faa40828c0e7) | 
| d3.forceEdgeBundling | [d3.forceBundle](https://github.com/upphiminn/d3.ForceBundle) | Force-directed edge bundling algorithm. Self-organise edges on thick mesh graphs to decrease visual clutter. | [US airline routes](http://bl.ocks.org/upphiminn/6515478), [FDEB on force-directed graph](https://bl.ocks.org/vasturiano/7c5f24ef7d4237f7eb33f17e59a6976e) |

Please get in touch for any additions/corrections to this list. And as always, use the force!