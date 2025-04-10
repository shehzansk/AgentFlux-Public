## AgentOps

<div align="center">
  <table border="0" cellspacing="0" cellpadding="0">
    <tr>
      <td style="padding-right: 30px;">
        <img src="main\public\agentops-logo.gif" alt="AgentOps Logo" width="300"/>
      </td>
      <td style="vertical-align: middle; font-size: 24px; font-weight: bold;">
        Agent Engineering for reliable & dynamic AI agents
      </td>
    </tr>
  </table>
</div>
<br/>
<div>
 <p>
   <span>Fine-Tuned Models:&nbsp;&nbsp;</span>
    <a href="https://huggingface.co/VidyutCx/mistral-prompttune">
      <img src="https://img.shields.io/badge/🤗_Model-Mistral_prompttune-blue?style=flat-square" alt="Prompt refinement Model">
    </a>
    <a href="https://huggingface.co/VidyutCx/deepseek-agentarchitect">
      <img src="https://img.shields.io/badge/🤗_Model-Deepseek_Agentarchitect-green?style=flat-square" alt="Agent archtect Model">
    </a>
  </p>
</div>


1. Overview:<br/>
- AgentOps is an advanced agent engineering platform that enables developers to build, test, visualize, and refine AI agent systems with unprecedented control and visibility. With an intuitive UI and powerful backend capabilities, AgentOps streamlines the process of creating reliable, dynamic agent graphs while providing comprehensive monitoring and optimization tools.

2. Key Features:
   - Interactive Playground Environment
    Create and manage multiple playgrounds for different agent projects
    Collaborative code editing with syntax highlighting and IntelliSense
    Built-in terminal for real-time code execution and feedback
    Agent Graph Visualization
    
    - Automatically extract and visualize agent relationships from code
    Interactive node-based graph representation of agent structures
    Visual indicators for model types and communication flows
    Intelligent Agent Refinement
    
    - Automated agent graph improvement suggestions
    Advanced diff comparison between original and refined code
    Selective merging of recommended changes
    Model Management
    
    - Associate specific models with agent sheets
    Control which LLMs are available for different agent components
    Track model performance and resource utilization
    Comprehensive Observation Tools
    
    - Historical tracking of agent refinements and changes
    Detailed diff reports with visual highlighting
    Performance metrics and comparison across agent versions

<br/>
<div align="center">
    <img src="main\public\vid1.gif" alt="AgentOps video1" width="800"/>
</div>
<br/>

**AgentOps Studios**

- Make studios with integrated EC2 configured containers to run your code.<br/>
- Visualize your agent graphs wihtout changing a single of code.
- Integrate with custom models from hugging face in a totally no-code environment.
- integrated loggers and profilers that save each of your runs/refines to facilitate state reversion and finegrained observations. 

<div>
<h3>Options for Agent Graphs Refinement</h3>
  <table border="3" cellspacing="0" cellpadding="0">
    <tr>
      <td style="padding-right: 30px;">
      Refine Prompts
      </td>
      <td style="vertical-align: middle;">
       Uses a fine tuned model for refining user given prompts, sets guardrails and system instructions out of the box.
      </td>
    </tr>
    <tr>
      <td style="padding-right: 30px;">
      Re-architect Graphs
      </td>
      <td style="vertical-align: middle;">
       Analyzes agent graphs to find God Tasks, breaks them into smaller modules, tries to optimize graphs using more modular structures. Dyanimcally shifts to better models for your tasks using hugging face's public endpoints for models.
      </td>
    </tr>
    <tr>
      <td style="padding-right: 30px;">
      Refinement Loop
      </td>
      <td style="vertical-align: middle;">
       Goes into a loop of refinement->execution->evaluation until certain output criterias set by you are met.
      </td>
    </tr>
  </table>
</div>
<br/>
<div>

<br/>
<div align="center">
    <img src="main\public\vid2.gif" alt="AgentOps video1" width="800"/>
</div>
<br/>

**AgentOps Observe**

- Loggers record your runs, save your refine merges.<br/>
- Visualize changes made by our models in specific refines in proper diff reports.
- Make changes from any state to revert back to it.
- integrated loggers and profilers injected directly into your code help visualize time taken by different agents within your graph and helps you decode bottlenecks and see refined outputs. 
