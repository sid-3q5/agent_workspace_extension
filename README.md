# agent_workspace_extension


Agent_registry -

agent_id: 
version_id: 
agent_name:
agent_type: prompt_based/tool_based/a2a/agent_as_a_tool
framework: langgraph/adk
description: 
instruction: 
system_prompt: 
tags: 
tools_id: 
output_type: streaming / non_streaming
metadata: user_data


-------------------------------------------

tool_registry

tool_id:
tool_name:
tool_type: http/mcp/agent_as_tool/code_based_tool
description
tags
http_url: optional
mcp_url: optional
mcp_endpoint: optional
function_code: str 
agent_id: 
agent_code: str
metadata: user_id/created_by/created_at

----

session_framework

session_id:
session_checkpoint: #last time what was the prompt and response
metadata: user_data

