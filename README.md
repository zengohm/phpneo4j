phpneo4j
========
<h1>Index</h1>
<dl class="index_list">
	<dt><a href="#neo4j">neo4j</a></dt>
	<dd><a href="#neo4j::__construct">neo4j::__construct</a></dd>
	<dd><a href="#neo4j::createNode">neo4j::createNode</a></dd>
	<dd><a href="#neo4j::getNode">neo4j::getNode</a></dd>
	<dd><a href="#neo4j::deleteNode">neo4j::deleteNode</a></dd>
	<dd><a href="#neo4j::createRelationship">neo4j::createRelationship</a></dd>
	<dd><a href="#neo4j::getRelationship">neo4j::getRelationship</a></dd>
	<dd><a href="#neo4j::deleteRelationship">neo4j::deleteRelationship</a></dd>
	<dd><a href="#neo4j::getPath">neo4j::getPath</a></dd>
	<dd><a href="#neo4j::getPaths">neo4j::getPaths</a></dd>
	<dd><a href="#neo4j::getNodeIndex">neo4j::getNodeIndex</a></dd>
	<dd><a href="#neo4j::deleteNodeIndex">neo4j::deleteNodeIndex</a></dd>
	<dd><a href="#neo4j::getRelationshipIndex">neo4j::getRelationshipIndex</a></dd>
	<dd><a href="#neo4j::deleteRelationshipIndex">neo4j::deleteRelationshipIndex</a></dd>
	<dd><a href="#neo4j::cypher">neo4j::cypher</a></dd>
	<dd><a href="#neo4j::query">neo4j::query</a></dd>
	<dd><a href="#neo4j::restAPI">neo4j::restAPI</a></dd>
</dl>
<dl class="index_list">
	<dt><a href="#neo4jNode">neo4jNode</a></dt>
	<dd><a href="#neo4jNode::getId">neo4jNode::getId</a></dd>
	<dd><a href="#neo4jNode::getUri">neo4jNode::getUri</a></dd>
	<dd><a href="#neo4jNode::save">neo4jNode::save</a></dd>
	<dd><a href="#neo4jNode::delete">neo4jNode::delete</a></dd>
	<dd><a href="#neo4jNode::getProperty">neo4jNode::getProperty</a></dd>
	<dd><a href="#neo4jNode::getAllProperties">neo4jNode::getAllProperties</a></dd>
	<dd><a href="#neo4jNode::setProperty">neo4jNode::setProperty</a></dd>
	<dd><a href="#neo4jNode::setAllProperties">neo4jNode::setAllProperties</a></dd>
	<dd><a href="#neo4jNode::deleteProperty">neo4jNode::deleteProperty</a></dd>
	<dd><a href="#neo4jNode::getRelationships">neo4jNode::getRelationships</a></dd>
	<dd><a href="#neo4jNode::getPathTo">neo4jNode::getPathTo</a></dd>
	<dd><a href="#neo4jNode::getPathFrom">neo4jNode::getPathFrom</a></dd>
	<dd><a href="#neo4jNode::getPathsTo">neo4jNode::getPathsTo</a></dd>
	<dd><a href="#neo4jNode::getPathsFrom">neo4jNode::getPathsFrom</a></dd>
	<dd><a href="#neo4jNode::traverseNodes">neo4jNode::traverseNodes</a></dd>
	<dd><a href="#neo4jNode::traversePaths">neo4jNode::traversePaths</a></dd>
	<dd><a href="#neo4jNode::traverseRelationships">neo4jNode::traverseRelationships</a></dd>
</dl>
<dl class="index_list">
	<dt><a href="#neo4jRelationship">neo4jRelationship</a></dt>
	<dd><a href="#neo4jRelationship::getId">neo4jRelationship::getId</a></dd>
	<dd><a href="#neo4jRelationship::getUri">neo4jRelationship::getUri</a></dd>
	<dd><a href="#neo4jRelationship::save">neo4jRelationship::save</a></dd>
	<dd><a href="#neo4jRelationship::delete">neo4jRelationship::delete</a></dd>
	<dd><a href="#neo4jRelationship::getProperty">neo4jRelationship::getProperty</a></dd>
	<dd><a href="#neo4jRelationship::getAllProperties">neo4jRelationship::getAllProperties</a></dd>
	<dd><a href="#neo4jRelationship::setProperty">neo4jRelationship::setProperty</a></dd>
	<dd><a href="#neo4jRelationship::setAllProperties">neo4jRelationship::setAllProperties</a></dd>
	<dd><a href="#neo4jRelationship::deleteProperty">neo4jRelationship::deleteProperty</a></dd>
	<dd><a href="#neo4jRelationship::startNode">neo4jRelationship::startNode</a></dd>
	<dd><a href="#neo4jRelationship::endNode">neo4jRelationship::endNode</a></dd>
	<dd><a href="#neo4jRelationship::getType">neo4jRelationship::getType</a></dd>
</dl>
<dl class="index_list">
	<dt><a href="#neo4jIndex">neo4jIndex</a></dt>
	<dd><a href="#neo4jIndex::getId">neo4jIndex::getId</a></dd>
	<dd><a href="#neo4jIndex::get">neo4jIndex::get</a></dd>
	<dd><a href="#neo4jIndex::getOrCreate">neo4jIndex::getOrCreate</a></dd>
	<dd><a href="#neo4jIndex::add">neo4jIndex::add</a></dd>
	<dd><a href="#neo4jIndex::remove">neo4jIndex::remove</a></dd>
	<dd><a href="#neo4jIndex::delete">neo4jIndex::delete</a></dd>
</dl>
<dl class="index_list">
	<dt><a href="#neo4jPath">neo4jPath</a></dt>
	<dd><a href="#neo4jPath::startNode">neo4jPath::startNode</a></dd>
	<dd><a href="#neo4jPath::endNode">neo4jPath::endNode</a></dd>
	<dd><a href="#neo4jPath::getLength">neo4jPath::getLength</a></dd>
	<dd><a href="#neo4jPath::getNodes">neo4jPath::getNodes</a></dd>
	<dd><a href="#neo4jPath::getRelationships">neo4jPath::getRelationships</a></dd>
</dl>
<h1 id="neo4j">neo4j</h1>
<dl>
	<dd><a href="#neo4j::__construct">neo4j::__construct</a></dd>
	<dd><a href="#neo4j::createNode">neo4j::createNode</a></dd>
	<dd><a href="#neo4j::getNode">neo4j::getNode</a></dd>
	<dd><a href="#neo4j::deleteNode">neo4j::deleteNode</a></dd>
	<dd><a href="#neo4j::createRelationship">neo4j::createRelationship</a></dd>
	<dd><a href="#neo4j::getRelationship">neo4j::getRelationship</a></dd>
	<dd><a href="#neo4j::deleteRelationship">neo4j::deleteRelationship</a></dd>
	<dd><a href="#neo4j::getPath">neo4j::getPath</a></dd>
	<dd><a href="#neo4j::getPaths">neo4j::getPaths</a></dd>
	<dd><a href="#neo4j::getNodeIndex">neo4j::getNodeIndex</a></dd>
	<dd><a href="#neo4j::deleteNodeIndex">neo4j::deleteNodeIndex</a></dd>
	<dd><a href="#neo4j::getRelationshipIndex">neo4j::getRelationshipIndex</a></dd>
	<dd><a href="#neo4j::deleteRelationshipIndex">neo4j::deleteRelationshipIndex</a></dd>
	<dd><a href="#neo4j::cypher">neo4j::cypher</a></dd>
	<dd><a href="#neo4j::query">neo4j::query</a></dd>
	<dd><a href="#neo4j::restAPI">neo4j::restAPI</a></dd>
</dl>
<h2>neo4j::__construct</h2>
<h3 id="neo4j___construct">public neo4j::__construct([string $host="localhost" [,int $port=7474 [,string $userpsw=""]]])</h3>
<p>Create a new neo4j connection object</p>
<dl>
	<dt>userpsw</dt>
	<dd>username:password</dd>
</dl>
<h2>neo4j::createNode</h2>
<h3 id="neo4j_createNode">public neo4jNode neo4j::createNode([array $properties=array()])</h3>
<p>Create a neo4jNode</p>
<h2>neo4j::getNode</h2>
<h3 id="neo4j_getNode">public neo4jNode neo4j::getNode(string $id)</h3>
<p>Get a neo4jNode by nodeId</p>
<h2>neo4j::deleteNode</h2>
<h3 id="neo4j_deleteNode">public neo4j::deleteNode(string $id)</h3>
<p>Delete a neo4jNode by nodeId</p>
<h2>neo4j::createRelationship</h2>
<h3 id="neo4j_createRelationship">public neo4jRelationship neo4j::createRelationship(mixed $start, mixed $to [,string $type="" [,array $properties=array()]])</h3>
<p>Create a neo4jRelationship</p>
<p>$start and $to can be nodeId or neo4jNode object.</p>
<h2>neo4j::getRelationship</h2>
<h3 id="neo4j_getRelationship">public neo4jRelationship neo4j::getRelationship(string $id)</h3>
<p>Get a neo4jRelationship by relationshipId</p>
<h2>neo4j::deleteRelationship</h2>
<h3 id="neo4j_deleteRelationship">public neo4j::deleteRelationship(string $id)</h3>
<p>Delete a neo4jRelationship by relationshipId</p>
<h2>neo4j::getPath</h2>
<h3 id="neo4j_getPath">public neo4jPath neo4j::getPath(mixed $start, mixed $to, string $type, int $algorithm [, array $option])</h3>
<p>Get a neo4jPath by conditions</p>
<dl>
	<dt>$algorithm</dt>
	<dd>NEO4J_PATH_SHORTESTPATH</dd>
	<dd>NEO4J_PATH_ALLSIMPLEPATHS</dd>
	<dd>NEO4J_PATH_ALLPATHS</dd>
	<dd>NEO4J_PATH_DIJKSTRA</dd>
</dl>
<dl>
	<dt>$option - An array of options to applay</dt>
	<dd>max_depth</dd>
	<dd>cost_property - only use for NEO4J_PATH_DIJKSTRA</dd>
</dl>
<h2>neo4j::getPaths</h2>
<h3 id="neo4j_getPaths">public neo4jPath neo4j::getPaths(mixed $start, mixed $to, string $type, int $algorithm [, array $option])</h3>
<p>Get all neo4jPathes by conditions</p>
<dl>
	<dt>$algorithm</dt>
	<dd>NEO4J_PATH_SHORTESTPATH</dd>
	<dd>NEO4J_PATH_ALLSIMPLEPATHS</dd>
	<dd>NEO4J_PATH_ALLPATHS</dd>
	<dd>NEO4J_PATH_DIJKSTRA</dd>
</dl>
<dl>
	<dt>$option - An array of options to applay</dt>
	<dd>max_depth</dd>
	<dd>cost_property - only use for NEO4J_PATH_DIJKSTRA</dd>
</dl>
<h2>neo4j::getNodeIndex</h2>
<h3 id="neo4j_getNodeIndex">public neo4jIndex neo4j::getNodeIndex(string $id)</h3>
<p>Get a neo4jIndex of neo4jNode by indexId</p>
<h2>neo4j::deleteNodeIndex</h2>
<h3 id="neo4j_deleteNodeIndex">public neo4j::deleteNodeIndex(string $id)</h3>
<p>Delete a neo4jIndex of neo4jNode by indexId</p>
<h2>neo4j::getRelationshipIndex</h2>
<h3 id="neo4j_getRelationshipIndex">public neo4jIndex neo4j::getRelationshipIndex(string $id)</h3>
<p>Get a neo4jIndex of neo4jRelationship by indexId</p>
<h2>neo4j::deleteRelationshipIndex</h2>
<h3 id="neo4j_deleteRelationshipIndex">public neo4j::deleteRelationshipIndex(string $id)</h3>
<p>Delete a neo4jIndex of neo4jRelationship by indexId</p>
<h2>neo4j::cypher</h2>
<h3 id="neo4j_cypher">public array neo4j::cypher(string $query [, array $params = array()])</h3>
<p>Query with cypher</p>
<h2>neo4j::query</h2>
<h3 id="neo4j_query">public array neo4j::query(string $query)</h3>
<p>Find node by query from an automatic index</p>
<h2>neo4j::restAPI</h2>
<h3 id="neo4j_restAPI">public array neo4j::restAPI(int $method, string $path [,array $data])</h3>
<p>Send a request by restAPI</p>
<dl>
	<dt>$method</dt>
	<dd>REST_METHOD_GET</dd>
	<dd>REST_METHOD_POST</dd>
	<dd>REST_METHOD_DELETE</dd>
	<dd>REST_METHOD_PUT</dd>
</dl>
<h1 id="neo4jNode">neo4jNode</h1>
<dl>
	<dd><a href="#neo4jNode::getId">neo4jNode::getId</a></dd>
	<dd><a href="#neo4jNode::getUri">neo4jNode::getUri</a></dd>
	<dd><a href="#neo4jNode::save">neo4jNode::save</a></dd>
	<dd><a href="#neo4jNode::delete">neo4jNode::delete</a></dd>
	<dd><a href="#neo4jNode::getProperty">neo4jNode::getProperty</a></dd>
	<dd><a href="#neo4jNode::getAllProperties">neo4jNode::getAllProperties</a></dd>
	<dd><a href="#neo4jNode::setProperty">neo4jNode::setProperty</a></dd>
	<dd><a href="#neo4jNode::setAllProperties">neo4jNode::setAllProperties</a></dd>
	<dd><a href="#neo4jNode::deleteProperty">neo4jNode::deleteProperty</a></dd>
	<dd><a href="#neo4jNode::getRelationships">neo4jNode::getRelationships</a></dd>
	<dd><a href="#neo4jNode::getPathTo">neo4jNode::getPathTo</a></dd>
	<dd><a href="#neo4jNode::getPathFrom">neo4jNode::getPathFrom</a></dd>
	<dd><a href="#neo4jNode::getPathsTo">neo4jNode::getPathsTo</a></dd>
	<dd><a href="#neo4jNode::getPathsFrom">neo4jNode::getPathsFrom</a></dd>
	<dd><a href="#neo4jNode::traverseNodes">neo4jNode::traverseNodes</a></dd>
	<dd><a href="#neo4jNode::traversePaths">neo4jNode::traversePaths</a></dd>
	<dd><a href="#neo4jNode::traverseRelationships">neo4jNode::traverseRelationships</a></dd>
</dl>
<h2>neo4jNode::getId</h2>
<h3 id="neo4jNode_getId">public string neo4jNode::getId()</h3>
<p>Get nodeId</p>
<h2>neo4jNode::getUri</h2>
<h3 id="neo4jNode_getUri">public string neo4jNode::getUri()</h3>
<p>Get uri</p>
<h2>neo4jNode::save</h2>
<h3 id="neo4jNode_save">public neo4jNode neo4jNode::save()</h3>
<p>Save self</p>
<h2>neo4jNode::delete</h2>
<h3 id="neo4jNode_delete">public neo4jNode::delete()</h3>
<p>Delete self</p>
<h2>neo4jNode::getProperty</h2>
<h3 id="neo4jNode_getProperty">public mix neo4jNode::getProperty(string $key)</h3>
<p>Get a property by key</p>
<h2>neo4jNode::getAllproperties</h2>
<h3 id="neo4jNode_getAllProperties">public array neo4jNode::getAllProperties()</h3>
<p>Get all properties</p>
<h2>neo4jNode::setProperty</h2>
<h3 id="neo4jNode_setProperty">public neo4jNode neo4jNode::setProperty(string $key,mix $value)</h3>
<p>Set a property</p>
<h2>neo4jNode::setAllProperties</h2>
<h3 id="neo4jNode_setAllProperties">public neo4jNode neo4jNode::setAllProperties(array $properties)</h3>
<p>Set all properties</p>
<h2>neo4jNode::deleteProperty</h2>
<h3 id="neo4jNode_deleteProperty">public neo4jNode neo4jNode::deleteProperty(string $key)</h3>
<p>Delete a property</p>
<h2>neo4jNode::getRelationships</h2>
<h3 id="neo4jNode_getRelationships">public array neo4jNode::getRelationships([int $direct = NEO4J_RELATIONSHIP_ALL [, array $typeList = array()]])</h3>
<p>Get all relationships</p>
<dl>
	<dt>$direct</dt>
	<dd>NEO4J_RELATIONSHIP_IN</dd>
	<dd>NEO4J_RELATIONSHIP_OUT</dd>
	<dd>NEO4J_RELATIONSHIP_ALL</dd>
</dl>
<h2>neo4jNode::getPathTo</h2>
<h3 id="neo4jNode_getPathTo">public neo4jPath neo4jNode::getPathTo(mixed $to, string $type, int $algorithm [, array $option])</h3>
<p>Get a neo4jPath by conditions</p>
<dl>
	<dt>$algorithm</dt>
	<dd>NEO4J_PATH_SHORTESTPATH</dd>
	<dd>NEO4J_PATH_ALLSIMPLEPATHS</dd>
	<dd>NEO4J_PATH_ALLPATHS</dd>
	<dd>NEO4J_PATH_DIJKSTRA</dd>
</dl>
<dl>
	<dt>$option - An array of options to applay</dt>
	<dd>max_depth</dd>
	<dd>cost_property - only use for NEO4J_PATH_DIJKSTRA</dd>
</dl>
<h2>neo4jNode::getPathFrom</h2>
<h3 id="neo4jNode_getPathFrom">public neo4jPath neo4jNode::getPathFrom(mixed $start, string $type, int $algorithm [, array $option])</h3>
<p>Get a neo4jPath by conditions</p>
<dl>
	<dt>$algorithm</dt>
	<dd>NEO4J_PATH_SHORTESTPATH</dd>
	<dd>NEO4J_PATH_ALLSIMPLEPATHS</dd>
	<dd>NEO4J_PATH_ALLPATHS</dd>
	<dd>NEO4J_PATH_DIJKSTRA</dd>
</dl>
<dl>
	<dt>$option - An array of options to applay</dt>
	<dd>max_depth</dd>
	<dd>cost_property - only use for NEO4J_PATH_DIJKSTRA</dd>
</dl>
<h2>neo4jNode::getPathsTo</h2>
<h3 id="neo4jNode_getPathsTo">public neo4jPath neo4jNode::getPathsTo(mixed $to, string $type, int $algorithm [, array $option])</h3>
<p>Get all neo4jPathes by conditions</p>
<dl>
	<dt>$algorithm</dt>
	<dd>NEO4J_PATH_SHORTESTPATH</dd>
	<dd>NEO4J_PATH_ALLSIMPLEPATHS</dd>
	<dd>NEO4J_PATH_ALLPATHS</dd>
	<dd>NEO4J_PATH_DIJKSTRA</dd>
</dl>
<dl>
	<dt>$option - An array of options to applay</dt>
	<dd>max_depth</dd>
	<dd>cost_property - only use for NEO4J_PATH_DIJKSTRA</dd>
</dl>
<h2>neo4jNode::getPathsFrom</h2>
<h3 id="neo4jNode_getPathsFrom">public neo4jPath neo4jNode::getPathsFrom(mixed $start, string $type, int $algorithm [, array $option])</h3>
<p>Get all neo4jPathes by conditions</p>
<dl>
	<dt>$algorithm</dt>
	<dd>NEO4J_PATH_SHORTESTPATH</dd>
	<dd>NEO4J_PATH_ALLSIMPLEPATHS</dd>
	<dd>NEO4J_PATH_ALLPATHS</dd>
	<dd>NEO4J_PATH_DIJKSTRA</dd>
</dl>
<dl>
	<dt>$option - An array of options to applay</dt>
	<dd>max_depth</dd>
	<dd>cost_property - only use for NEO4J_PATH_DIJKSTRA</dd>
</dl>
<h2>neo4jNode::traverseNodes</h2>
<h3 id="neo4jNode_traverseNodes">public array neo4jNode::traverseNodes(array $option)</h3>
<p>Traverse nodes</p>
<dl>
	<dt>$option</dt>
	<dd>order - [ breadth_first | depth_first ]</dd>
	<dd>relationships - [ all | in | out ]</dd>
	<dd>uniqueness - [ node_global | none | relationship_global | node_path | relationship_path ]</dd>
	<dd>return_filter - [ all | all_but_start_node ]</dd>
	<dd>prune_evaluator</dd>
	<dd>max_depth</dd>
</dl>
<h2>neo4jNode::traversePaths</h2>
<h3 id="neo4jNode_traversePaths">public array neo4jNode::traversePaths(array $option)</h3>
<p>Traverse paths</p>
<dl>
	<dt>$option</dt>
	<dd>order - [ breadth_first | depth_first ]</dd>
	<dd>relationships - [ all | in | out ]</dd>
	<dd>uniqueness - [ node_global | none | relationship_global | node_path | relationship_path ]</dd>
	<dd>return_filter - [ all | all_but_start_node ]</dd>
	<dd>prune_evaluator</dd>
	<dd>max_depth</dd>
</dl>
<h2>neo4jNode::traverseRelationships</h2>
<h3 id="neo4jNode_traverseRelationships">public array neo4jNode::traverseRelationships(array $option)</h3>
<p>Traverse relationships</p>
<dl>
	<dt>$option</dt>
	<dd>order - [ breadth_first | depth_first ]</dd>
	<dd>relationships - [ all | in | out ]</dd>
	<dd>uniqueness - [ node_global | none | relationship_global | node_path | relationship_path ]</dd>
	<dd>return_filter - [ all | all_but_start_node ]</dd>
	<dd>prune_evaluator</dd>
	<dd>max_depth</dd>
</dl>
<h1 id="neo4jRelationship">neo4jRelationship</h1>
<dl>
	<dd><a href="#neo4jRelationship::getId">neo4jRelationship::getId</a></dd>
	<dd><a href="#neo4jRelationship::getUri">neo4jRelationship::getUri</a></dd>
	<dd><a href="#neo4jRelationship::save">neo4jRelationship::save</a></dd>
	<dd><a href="#neo4jRelationship::delete">neo4jRelationship::delete</a></dd>
	<dd><a href="#neo4jRelationship::getProperty">neo4jRelationship::getProperty</a></dd>
	<dd><a href="#neo4jRelationship::getAllProperties">neo4jRelationship::getAllProperties</a></dd>
	<dd><a href="#neo4jRelationship::setProperty">neo4jRelationship::setProperty</a></dd>
	<dd><a href="#neo4jRelationship::setAllProperties">neo4jRelationship::setAllProperties</a></dd>
	<dd><a href="#neo4jRelationship::deleteProperty">neo4jRelationship::deleteProperty</a></dd>
	<dd><a href="#neo4jRelationship::startNode">neo4jRelationship::startNode</a></dd>
	<dd><a href="#neo4jRelationship::endNode">neo4jRelationship::endNode</a></dd>
	<dd><a href="#neo4jRelationship::getType">neo4jRelationship::getType</a></dd>
</dl>
<h2>neo4jRelationship::getId</h2>
<h3 id="neo4jRelationship_getId">public string neo4jRelationship::getId()</h3>
<p>Get relationshipId</p>
<h2>neo4jRelationship::getUri</h2>
<h3 id="neo4jRelationship_getUri">public string neo4jRelationship::getUri()</h3>
<p>Get uri</p>
<h2>neo4jRelationship::save</h2>
<h3 id="neo4jRelationship_save">public neo4jRelationship neo4jRelationship::save()</h3>
<p>Save self</p>
<h2>neo4jRelationship::delete</h2>
<h3 id="neo4jRelationship_delete">public neo4jRelationship::delete()</h3>
<p>Delete self</p>
<h2>neo4jRelationship::getProperty</h2>
<h3 id="neo4jRelationship_getProperty">public mix neo4jRelationship::getProperty(string $key)</h3>
<p>Get a property by key</p>
<h2>neo4jRelationship::getAllProperties</h2>
<h3 id="neo4jRelationship_getAllProperties">public array neo4jRelationship::getAllProperties()</h3>
<p>Get all properties</p>
<h2>neo4jRelationship::setProperty</h2>
<h3 id="neo4jRelationship_setProperty">public neo4jRelationship neo4jRelationship::setProperty(string $key,mix $value)</h3>
<p>Set a property</p>
<h2>neo4jRelationship::setAllProperties</h2>
<h3 id="neo4jRelationship_setAllProperties">public neo4jRelationship neo4jRelationship::setAllProperties(array $properties)</h3>
<p>Set all properties</p>
<h2>neo4jRelationship::deleteProperty</h2>
<h3 id="neo4jRelationship_deleteProperty">public neo4jRelationship neo4jRelationship::deleteProperty(string $key)</h3>
<p>Delete a property</p>
<h2>neo4jRelationship::startNode</h2>
<h3 id="neo4jRelationship_startNode">public neo4jNode neo4jRelationship::startNode()</h3>
<p>Get start node</p>
<h2>neo4jRelationship::endNode</h2>
<h3 id="neo4jRelationship_endNode">public neo4jNode neo4jRelationship::endNode()</h3>
<p>Get end node</p>
<h2>neo4jRelationship::getType</h2>
<h3 id="neo4jRelationship_getType">public string neo4jRelationship::getType()</h3>
<p>Get type</p>
<h1 id="neo4jIndex">neo4jIndex</h1>
<dl>
	<dd><a href="#neo4jIndex::getId">neo4jIndex::getId</a></dd>
	<dd><a href="#neo4jIndex::get">neo4jIndex::get</a></dd>
	<dd><a href="#neo4jIndex::getOrCreate">neo4jIndex::getOrCreate</a></dd>
	<dd><a href="#neo4jIndex::add">neo4jIndex::add</a></dd>
	<dd><a href="#neo4jIndex::remove">neo4jIndex::remove</a></dd>
	<dd><a href="#neo4jIndex::delete">neo4jIndex::delete</a></dd>
</dl>
<h2>neo4jIndex::getId</h2>
<h3 id="neo4jIndex_getId">public string neo4jIndex::getId()</h3>
<p>Get indexId</p>
<h2>neo4jIndex::get</h2>
<h3 id="neo4jIndex_get">public mix neo4jIndex::get(string $key, string $value)</h3>
<p>Get objects by $key and $value</p>
<h2>neo4jIndex::getOrCreate</h2>
<h3 id="neo4jIndex_getOrCreate">public mix neo4jIndex::getOrCreate(mixed $obj, string $key, string $value)</h3>
<p>Get or create an object by $key and $value</p>
<h2>neo4jIndex::add</h2>
<h3 id="neo4jIndex_add">public neo4jIndex neo4jIndex::add(mixed $obj, string $key, string $value)</h3>
<p>Add an object to the index</p>
<h2>neo4jIndex::remove</h2>
<h3 id="neo4jIndex_remove">public neo4jIndex neo4jIndex::remove(mixed $obj, string $key, string $value)</h3>
<p>Remove an object from the index</p>
<h2>neo4jIndex::delete</h2>
<h3 id="neo4jIndex_delete">public neo4jIndex::delete()</h3>
<p>Delete self</p>
<h1 id="neo4jPath">neo4jPath</h1>
<dl>
	<dd><a href="#neo4jPath::startNode">neo4jPath::startNode</a></dd>
	<dd><a href="#neo4jPath::endNode">neo4jPath::endNode</a></dd>
	<dd><a href="#neo4jPath::getLength">neo4jPath::getLength</a></dd>
	<dd><a href="#neo4jPath::getNodes">neo4jPath::getNodes</a></dd>
	<dd><a href="#neo4jPath::getRelationships">neo4jPath::getRelationships</a></dd>
</dl>
<h2>neo4jPath::startNode</h2>
<h3 id="neo4jPath_startNode">public neo4jNode neo4jPath::startNode()</h3>
<p>Get start node</p>
<h2>neo4jPath::endNode</h2>
<h3 id="neo4jPath_endNode">public neo4jNode neo4jPath::endNode()</h3>
<p>Get end node</p>
<h2>neo4jPath::getLength</h2>
<h3 id="neo4jPath_getLength">public int neo4jPath::getLength()</h3>
<p>Get length</p>
<h2>neo4jPath::getNodes</h2>
<h3 id="neo4jPath_getNodes">public array neo4jPath::getNodes()</h3>
<p>Get all nodes</p>
<h2>neo4jPath::getRelationships</h2>
<h3 id="neo4jPath_getRelationships">public array neo4jPath::getRelationships()</h3>
<p>Get all relationships</p>
