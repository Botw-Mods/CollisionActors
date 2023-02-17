# CollisionActors

Vanilla Actors with Collision (I.e. CollisionActors) is a mass set of actors that mirrors every applicable vanilla actor in the game, but with added rigid body physics.

This is done because Nintendo baked the entire map into static-compound physics and removed the rigid-bodies from there (vanilla) actors.
In other words, we need to re-add the rigid-body physics to have collision in our modded maps. (At least until we can also bake the map, which is on it's way.)

---

To use C-Actors, edit your map normally with Ice-Spear, but append `C` to the end of the `UnitConfigName` to make it a CollisionActor. Then run [ActorLoader](https://github.com/ArchLeaders/ActorLoader#readme) to download and copy the correct actors into your mod.
