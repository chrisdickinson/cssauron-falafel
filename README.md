# cssauron-falafel

cssauron bindings for falafel / esprima JS ASTs.

it shortens the esprima names because holy god they're long.

# node types

    LabeledStatement	    ->	label
    BlockStatement	        ->	block
    Program	                ->	root
    ExpressionStatement	    ->	expr
    ConditionalExpression	->	ternary
    IfStatement	        	->	if
    BreakStatement	    	->	break
    ContinueStatement		->	continue
    WithStatement	    	->	with
    SwitchStatement	    	->	switch
    ReturnStatement	    	->	return
    ThrowStatement	    	->	throw
    TryStatement	    	->	try
    WhileStatement	    	->	while
    DoWhileStatement		->	do-while
    ForStatement	    	->	for
    ForInStatement	    	->	for-in
    FunctionDeclaration		->	function
    VariableDeclaration		->	variable-decl
    VariableDeclarator		->	variable
    LogicalExpression		->	binary
    BinaryExpression		->	binary
    AssignmentExpression	->	assign
    ArrayExpression	    	->	array
    ObjectExpression		->	object
    ObjectKeyExpression		->	key
    FunctionExpression		->	function
    SequenceExpression		->	sequence
    UpdateExpression		->	update
    UnaryExpression	    	->	unary
    CallExpression	    	->	call
    NewExpression	    	->	new
    MemberExpression		->	lookup
    SwitchClause	    	->	case
    CatchClause	        	->	catch
    DebuggerStatement		->	debugger
    ThisExpression	    	->	this
    Identifier	        	->	id
    Literal	            	->	literal

# license

MIT
