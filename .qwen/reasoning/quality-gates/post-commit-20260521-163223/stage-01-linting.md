# Stage 1: Linting & Code Quality

**Status:** FAIL
**Tools Run:** 2


### Debug Statements in src/app/page.tsx
```
37:              onFastForward={() => console.log('FF')}
38:              onRewind={() => console.log('REW')}
```
### Debug Statements in src/components/canvas/CodeflowCanvas.tsx
```
91:      output: 'console.log("Hello")',
```
### Debug Statements in src/lib/codeflow/agent.ts
```
33:    console.log('[codeflow-agent] Agent orchestrator initialized with config:', this.config);
```
### Debug Statements in src/lib/codeflow/analysis.ts
```
33:    console.log('[codeflow-analysis] Analysis engine initialized');
109:    // Check for console.log
```
### Debug Statements in src/lib/codeflow/canvas.ts
```
143:      console.log('[canvas] fitView called');
```
### Debug Statements in src/lib/codeflow/coderag.ts
```
20:    console.log('[coderag] Code RAG initialized');
137:      console.log('[coderag] Embedding index updated');
```
### Debug Statements in src/lib/codeflow/dtwin.ts
```
18:    console.log('[codeflow-dtwin] Digital twin engine initialized');
```
### Debug Statements in src/lib/codeflow/evolution.ts
```
40:    console.log('[codeflow-evolution] Evolution engine initialized with config:', this.config);
```
### Debug Statements in src/lib/codeflow/execution.ts
```
25:    console.log('[codeflow-execution] Engine initialized with config:', this.workspace);
114:  if (code.includes('console.log')) {
```
### Debug Statements in src/lib/codeflow/mcp.ts
```
18:    console.log(`[codeflow-mcp] Tool registered: ${tool.name}`);
23:    console.log(`[codeflow-mcp] Tool unregistered: ${name}`);
50:      console.log(`[codeflow-mcp] Agent registered: ${agentId}`);
```
### Debug Statements in src/lib/codeflow/prd.ts
```
21:    console.log('[codeflow-prd] PRD processor initialized');
```
### Debug Statements in src/lib/codeflow/versioning.ts
```
16:    console.log('[codeflow-versioning] Versioning manager initialized');
43:      console.log(`[codeflow-versioning] Checked out ${versionId}`);
```
### Debug Statements in src/types/codeflow-agent.ts
```
15:export type AgentType = 'coder' | 'reviewer' | 'tester' | 'planner' | 'researcher' | 'debugger';
```
