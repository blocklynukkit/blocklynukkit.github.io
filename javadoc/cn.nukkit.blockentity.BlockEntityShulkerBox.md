<div class="summary">
<ul class="blockList">
<li class="blockList">  
<li class="blockList"><a name="field.summary">
<!--   -->
</a>
<h3>成员变量一览</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Field Summary table, listing fields, and an explanation">
<caption><span>成员变量</span><span class="tabEnd"> </span></caption>
<tr>
<th>修饰符和类</th>
<th>成员变量描述</th>
</tr>
<tr class="altColor">
<td class="colFirst"><code>protected <a  title="class in cn.nukkit.inventory">ShulkerBoxInventory</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >inventory</a></span></code> </td>
</tr>
</table>
<ul class="blockList">
<li class="blockList"><a name="fields.inherited.from.class.cn.nukkit.blockentity.BlockEntity">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.blockentity.<a  title="class in cn.nukkit.blockentity">BlockEntity</a></h3>
<code><a >BANNER</a>, <a >BEACON</a>, <a >BED</a>, <a >BREWING_STAND</a>, <a >CAULDRON</a>, <a >CHEST</a>, <a >chunk</a>, <a >closed</a>, <a >COMPARATOR</a>, <a >count</a>, <a >DAYLIGHT_DETECTOR</a>, <a >ENCHANT_TABLE</a>, <a >ENDER_CHEST</a>, <a >FLOWER_POT</a>, <a >FURNACE</a>, <a >HOPPER</a>, <a >id</a>, <a >ITEM_FRAME</a>, <a >JUKEBOX</a>, <a >lastUpdate</a>, <a >MOB_SPAWNER</a>, <a >movable</a>, <a >MOVING_BLOCK</a>, <a >MUSIC</a>, <a >name</a>, <a >namedTag</a>, <a >PISTON_ARM</a>, <a >server</a>, <a >SHULKER_BOX</a>, <a >SIGN</a>, <a >SKULL</a>, <a >timing</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="fields.inherited.from.class.cn.nukkit.level.Position">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.level.<a  title="class in cn.nukkit.level">Position</a></h3>
<code><a >level</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="fields.inherited.from.class.cn.nukkit.math.Vector3">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.math.<a  title="class in cn.nukkit.math">Vector3</a></h3>
<code><a >x</a>, <a >y</a>, <a >z</a></code></li>
</ul>
</li>
</ul>
<!-- ======== CONSTRUCTOR SUMMARY ======== -->
<ul class="blockList">
<li class="blockList"><a name="constructor.summary">
<!--   -->
</a>
<h3>构造函数一览</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Constructor Summary table, listing constructors, and an explanation">
<caption><span>构造函数</span><span class="tabEnd"> </span></caption>
<tr>
<th>构造函数描述</th>
</tr>
<tr class="altColor">
<td class="colOne"><code><span class="memberNameLink"><a >BlockEntityShulkerBox</a></span>(<a  title="interface in cn.nukkit.level.format">FullChunk</a> chunk,
                     <a  title="class in cn.nukkit.nbt.tag">CompoundTag</a> nbt)</code> </td>
</tr>
</table>
</li>
</ul>
<!-- ========== METHOD SUMMARY =========== -->
<ul class="blockList">
<li class="blockList"><a name="method.summary">
<!--   -->
</a>
<h3>成员函数一览</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Method Summary table, listing methods, and an explanation">
<caption><span id="t0" class="activeTableTab"><span>All Methods</span><span class="tabEnd"> </span></span><span id="t2" class="tableTab"><span><a >Instance Methods</a></span><span class="tabEnd"> </span></span><span id="t4" class="tableTab"><span><a >Concrete Methods</a></span><span class="tabEnd"> </span></span></caption>
<tr>
<th>修饰符和类</th>
<th>成员函数描述</th>
</tr>
<tr id="i0" class="altColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >close</a></span>()</code> </td>
</tr>
<tr id="i1" class="rowColor">
<td class="colFirst"><code><a  title="class in cn.nukkit.inventory">BaseInventory</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getInventory</a></span>()</code> </td>
</tr>
<tr id="i2" class="altColor">
<td class="colFirst"><code><a  title="class in cn.nukkit.item">Item</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getItem</a></span>(int index)</code>
<div class="block">返回一个存储在容器里的物品的<code>Item</code>对象。<br/>
 Returns an item that stores in this container, as an <code>Item</code> object.</div>
</td>
</tr>
<tr id="i3" class="rowColor">
<td class="colFirst"><code><a  title="class or interface in java.lang">String</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getName</a></span>()</code>
<div class="block">返回这个事物的名字。<br/>
 Gets the name of this object.</div>
</td>
</tr>
<tr id="i4" class="altColor">
<td class="colFirst"><code><a  title="class in cn.nukkit.inventory">ShulkerBoxInventory</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getRealInventory</a></span>()</code> </td>
</tr>
<tr id="i5" class="rowColor">
<td class="colFirst"><code>int</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getSize</a></span>()</code>
<div class="block">返回这个容器最多能包含的物品数量。<br/>
 Returns the max number of items that this container can contain.</div>
</td>
</tr>
<tr id="i6" class="altColor">
<td class="colFirst"><code>protected int</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getSlotIndex</a></span>(int index)</code> </td>
</tr>
<tr id="i7" class="rowColor">
<td class="colFirst"><code><a  title="class in cn.nukkit.nbt.tag">CompoundTag</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getSpawnCompound</a></span>()</code> </td>
</tr>
<tr id="i8" class="altColor">
<td class="colFirst"><code>boolean</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >hasName</a></span>()</code>
<div class="block">返回这个事物是否有名字。<br/>
 Whether this object has a name.</div>
</td>
</tr>
<tr id="i9" class="rowColor">
<td class="colFirst"><code>protected void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >initBlockEntity</a></span>()</code> </td>
</tr>
<tr id="i10" class="altColor">
<td class="colFirst"><code>boolean</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >isBlockEntityValid</a></span>()</code> </td>
</tr>
<tr id="i11" class="rowColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >saveNBT</a></span>()</code> </td>
</tr>
<tr id="i12" class="altColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >setItem</a></span>(int index,
       <a  title="class in cn.nukkit.item">Item</a> item)</code>
<div class="block">把一个物品存储进容器。<br/>
 Sets or stores this item into this container.</div>
</td>
</tr>
<tr id="i13" class="rowColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >setName</a></span>(<a  title="class or interface in java.lang">String</a> name)</code>
<div class="block">设置或更改这个事物的名字。<br/>
 Changes the name of this object, or names it.</div>
</td>
</tr>
</table>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.blockentity.BlockEntitySpawnable">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.blockentity.<a  title="class in cn.nukkit.blockentity">BlockEntitySpawnable</a></h3>
<code><a >spawnTo</a>, <a >spawnToAll</a>, <a >updateCompoundTag</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.blockentity.BlockEntity">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.blockentity.<a  title="class in cn.nukkit.blockentity">BlockEntity</a></h3>
<code><a >createBlockEntity</a>, <a >getBlock</a>, <a >getCleanedNBT</a>, <a >getDefaultCompound</a>, <a >getId</a>, <a >getSaveId</a>, <a >isMovable</a>, <a >onBreak</a>, <a >onUpdate</a>, <a >registerBlockEntity</a>, <a >scheduleUpdate</a>, <a >setDirty</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.level.Position">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.level.<a  title="class in cn.nukkit.level">Position</a></h3>
<code><a >abs</a>, <a >add</a>, <a >add</a>, <a >add</a>, <a >add</a>, <a >ceil</a>, <a >clone</a>, <a >divide</a>, <a >floor</a>, <a >fromObject</a>, <a >fromObject</a>, <a >getChunk</a>, <a >getLevel</a>, <a >getLevelBlock</a>, <a >getLocation</a>, <a >getSide</a>, <a >getSide</a>, <a >isValid</a>, <a >multiply</a>, <a >round</a>, <a >setComponents</a>, <a >setLevel</a>, <a >setStrong</a>, <a >setWeak</a>, <a >subtract</a>, <a >subtract</a>, <a >subtract</a>, <a >subtract</a>, <a >subtract</a>, <a >toString</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.math.Vector3">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.math.<a  title="class in cn.nukkit.math">Vector3</a></h3>
<code><a >asBlockVector3</a>, <a >asVector3f</a>, <a >cross</a>, <a >distance</a>, <a >distanceSquared</a>, <a >dot</a>, <a >down</a>, <a >down</a>, <a >east</a>, <a >east</a>, <a >equals</a>, <a >getChunkX</a>, <a >getChunkZ</a>, <a >getFloorX</a>, <a >getFloorY</a>, <a >getFloorZ</a>, <a >getForward</a>, <a >getIntermediateWithXValue</a>, <a >getIntermediateWithYValue</a>, <a >getIntermediateWithZValue</a>, <a >getRight</a>, <a >getSouth</a>, <a >getUp</a>, <a >getWest</a>, <a >getX</a>, <a >getY</a>, <a >getZ</a>, <a >hashCode</a>, <a >length</a>, <a >lengthSquared</a>, <a >maxPlainDistance</a>, <a >maxPlainDistance</a>, <a >maxPlainDistance</a>, <a >maxPlainDistance</a>, <a >maxPlainDistance</a>, <a >normalize</a>, <a >north</a>, <a >north</a>, <a >rawHashCode</a>, <a >south</a>, <a >south</a>, <a >up</a>, <a >up</a>, <a >west</a>, <a >west</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.java.lang.Object">
<!--   -->
</a>
<h3>继承自类 java.lang.<a  title="class or interface in java.lang">Object</a></h3>
<code><a  title="class or interface in java.lang">finalize</a>, <a  title="class or interface in java.lang">getClass</a>, <a  title="class or interface in java.lang">notify</a>, <a  title="class or interface in java.lang">notifyAll</a>, <a  title="class or interface in java.lang">wait</a>, <a  title="class or interface in java.lang">wait</a>, <a  title="class or interface in java.lang">wait</a></code></li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
