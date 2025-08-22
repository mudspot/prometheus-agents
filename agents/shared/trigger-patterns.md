# Systematic Trigger Patterns for Advanced Reasoning

## Universal Activation Patterns

### 1. Complexity-Based Triggers

**AUTOMATIC ACTIVATION RULES:**
```yaml
task_complexity_thresholds:
  sequential_thinking_activation:
    step_count: ">= 3 distinct steps required"
    decision_points: ">= 2 branching decisions"
    stakeholder_impact: ">= 3 affected systems/teams"
    time_horizon: ">= 1 week implementation"
    rollback_complexity: "Manual intervention required"
    
  zen_mcp_activation:
    code_quality_categories: ">= 2 (security, performance, maintainability)"
    system_impact: "Core functionality affected"
    user_impact: ">= 100 users affected"
    data_sensitivity: "PII, financial, or confidential data involved"
    compliance_requirements: "Any regulatory standard involved"
    
  consensus_validation_activation:
    decision_criticality: "Production deployment"
    technology_selection: "Framework, library, or infrastructure choice"
    architecture_changes: "System boundaries or patterns affected"
    security_implementations: "Authentication, authorization, encryption"
    performance_targets: ">= 20% performance change expected"
```

### 2. Domain-Specific Triggers

**ARCHITECT TRIGGERS:**
```yaml
automatic_architecture_analysis:
  system_design:
    component_count: ">= 5 interacting components"
    integration_points: ">= 3 external systems"
    data_flow_complexity: "Multi-step data transformation"
    scalability_requirements: ">= 10x current capacity"
    
  migration_planning:
    affected_services: ">= 3 services to migrate"
    data_migration_size: ">= 1GB data"
    downtime_constraints: "< 4 hours allowed"
    rollback_complexity: "Multi-step rollback required"
    
  technology_evaluation:
    alternatives_count: ">= 3 technology options"
    evaluation_criteria: ">= 5 decision factors"
    long_term_impact: ">= 2 years commitment"
    team_learning_curve: ">= 1 month ramp-up"
```

**BACKEND DEVELOPER TRIGGERS:**
```yaml
automatic_code_analysis:
  performance_investigation:
    response_time: ">= 500ms endpoint response"
    query_time: ">= 100ms database query"
    memory_usage: ">= 20% increase"
    cpu_utilization: ">= 80% sustained"
    
  bug_investigation:
    error_frequency: ">= 5 occurrences/hour"
    user_impact: ">= 10 users affected"
    system_component_count: ">= 3 components involved"
    reproduction_steps: ">= 3 steps to reproduce"
    
  security_hardening:
    vulnerability_severity: "Medium or higher CVSS score"
    data_exposure_risk: "Any PII or sensitive data"
    access_control_changes: "Authentication or authorization modifications"
    external_integration: "Third-party API or service integration"
```

**QUALITY SPECIALIST TRIGGERS:**
```yaml
automatic_quality_assessment:
  security_analysis:
    owasp_categories: ">= 1 OWASP Top 10 category"
    vulnerability_count: ">= 2 potential vulnerabilities"
    compliance_scope: "Any regulatory requirement"
    threat_vectors: ">= 2 possible attack vectors"
    
  performance_analysis:
    bottleneck_areas: ">= 2 performance bottlenecks"
    load_increase: ">= 50% traffic increase expected"
    resource_constraints: "Memory, CPU, or storage limitations"
    user_experience_impact: "Core user flow affected"
    
  comprehensive_audit:
    code_quality_issues: ">= 3 quality categories affected"
    technical_debt_level: "High or critical technical debt"
    test_coverage: "< 80% code coverage"
    documentation_gaps: ">= 3 undocumented components"
```

### 3. Workflow Integration Triggers

**CASCADING WORKFLOW ACTIVATION:**
```yaml
workflow_cascade_patterns:
  investigation_cascade:
    trigger: "Complex bug with unknown root cause"
    sequence:
      1: "zen_debug for systematic analysis"
      2: "sequential_thinking for hypothesis development"
      3: "zen_consensus for solution validation"
      
  optimization_cascade:
    trigger: "Performance degradation >= 20%"
    sequence:
      1: "zen_analyze for bottleneck identification"
      2: "zen_tracer for execution flow analysis"
      3: "sequential_thinking for optimization planning"
      4: "zen_refactor for implementation"
      5: "zen_testgen for regression prevention"
      
  security_cascade:
    trigger: "Security vulnerability detected"
    sequence:
      1: "zen_secaudit for comprehensive analysis"
      2: "sequential_thinking for threat prioritization"
      3: "zen_consensus for remediation strategy"
      4: "zen_planner for implementation roadmap"
      
  architecture_cascade:
    trigger: "System design complexity >= threshold"
    sequence:
      1: "sequential_thinking for problem decomposition"
      2: "zen_analyze for pattern identification"
      3: "zen_consensus for architecture validation"
      4: "zen_planner for implementation strategy"
```

### 4. Context-Aware Activation

**ENVIRONMENTAL TRIGGERS:**
```yaml
context_based_activation:
  production_environment:
    trigger_sensitivity: "Lower thresholds for production issues"
    consensus_requirement: "Mandatory for production changes"
    documentation_requirement: "Full documentation required"
    rollback_planning: "Mandatory rollback plan"
    
  development_environment:
    trigger_sensitivity: "Higher thresholds for experimental work"
    consensus_requirement: "Optional for non-critical changes"
    documentation_requirement: "Basic documentation sufficient"
    rollback_planning: "Simple rollback acceptable"
    
  critical_systems:
    trigger_sensitivity: "Lowest thresholds"
    consensus_requirement: "Multi-model consensus mandatory"
    documentation_requirement: "Comprehensive documentation"
    validation_requirement: "Extended testing required"
    
  experimental_features:
    trigger_sensitivity: "Highest thresholds"
    consensus_requirement: "Single model acceptable"
    documentation_requirement: "Minimal documentation"
    validation_requirement: "Basic testing sufficient"
```

### 5. Agent Coordination Triggers

**CROSS-AGENT ACTIVATION:**
```yaml
collaborative_triggers:
  feature_development:
    trigger: "New feature affecting >= 3 system layers"
    participants: ["architect", "backend-developer", "frontend-developer", "test-engineer"]
    coordination_pattern: "Sequential design → Parallel implementation → Integrated testing"
    
  security_hardening:
    trigger: "Security issue affecting >= 2 system components"
    participants: ["quality-specialist", "architect", "backend-developer", "devops-engineer"]
    coordination_pattern: "Parallel analysis → Consensus planning → Coordinated implementation"
    
  performance_optimization:
    trigger: "Performance issue affecting >= 3 performance metrics"
    participants: ["quality-specialist", "backend-developer", "data-engineer", "devops-engineer"]
    coordination_pattern: "Layered analysis → Integrated optimization → Comprehensive validation"
    
  system_migration:
    trigger: "Migration affecting >= 5 system components"
    participants: ["architect", "backend-developer", "data-engineer", "devops-engineer", "test-engineer"]
    coordination_pattern: "Architecture planning → Implementation sequencing → Migration execution"
```

### 6. Failure Detection and Response Triggers

**AUTOMATIC INTERVENTION PATTERNS:**
```yaml
failure_response_triggers:
  quality_degradation:
    trigger: "Code quality metrics below threshold"
    response: "zen_codereview + zen_refactor + consensus validation"
    escalation: "Quality specialist intervention if automated fixes insufficient"
    
  security_vulnerability:
    trigger: "Security scan detecting vulnerabilities"
    response: "zen_secaudit + immediate consensus + emergency planning"
    escalation: "Immediate production protection measures"
    
  performance_regression:
    trigger: "Performance metrics degrading >= 25%"
    response: "zen_analyze + zen_debug + performance optimization cascade"
    escalation: "Infrastructure scaling or emergency rollback"
    
  system_instability:
    trigger: "Error rates >= 5% or availability < 99%"
    response: "zen_debug + sequential_thinking + emergency response"
    escalation: "Full incident response with all agents"
```

### 7. Learning and Adaptation Triggers

**CONTINUOUS IMPROVEMENT ACTIVATION:**
```yaml
learning_triggers:
  pattern_recognition:
    trigger: "Similar issues occurring >= 3 times"
    response: "Extract pattern to shared knowledge + automated detection"
    learning: "Update trigger thresholds and response patterns"
    
  success_optimization:
    trigger: "Successful resolution pattern identified"
    response: "Document pattern + add to automated workflows"
    learning: "Optimize trigger sensitivity for similar cases"
    
  failure_analysis:
    trigger: "Resolution unsuccessful or suboptimal"
    response: "zen_debug failure + sequential_thinking for improvement"
    learning: "Adjust triggers and escalation patterns"
    
  efficiency_improvement:
    trigger: "Workflow taking >= 50% longer than baseline"
    response: "zen_analyze workflow + optimize trigger patterns"
    learning: "Refine automation and reduce manual intervention"
```

### 8. Implementation Guidelines

**TRIGGER CONFIGURATION:**
```elixir
defmodule TriggerSystem do
  @moduledoc """
  Systematic trigger pattern implementation for automated reasoning activation
  """
  
  def evaluate_triggers(context) do
    %{
      complexity: assess_complexity(context),
      domain_specific: check_domain_triggers(context),
      workflow_cascade: evaluate_workflow_needs(context),
      context_sensitivity: assess_environmental_factors(context),
      coordination_needs: check_cross_agent_requirements(context),
      failure_detection: monitor_failure_indicators(context),
      learning_opportunities: identify_improvement_patterns(context)
    }
    |> determine_activation_pattern()
    |> execute_triggered_workflows()
  end
  
  defp assess_complexity(context) do
    %{
      step_count: count_required_steps(context),
      decision_points: identify_decision_branches(context),
      stakeholder_impact: assess_impact_scope(context),
      rollback_complexity: evaluate_rollback_requirements(context)
    }
  end
  
  defp execute_triggered_workflows(activation_pattern) do
    activation_pattern
    |> Enum.map(&activate_workflow/1)
    |> Task.async_stream(&execute_workflow/1)
    |> Enum.to_list()
  end
end
```

**ACTIVATION VERIFICATION:**
```yaml
verification_checklist:
  - [ ] Complexity thresholds configured for all agents
  - [ ] Domain-specific triggers implemented
  - [ ] Workflow cascade patterns active
  - [ ] Context-aware sensitivity implemented
  - [ ] Cross-agent coordination triggers working
  - [ ] Failure detection and response active
  - [ ] Learning and adaptation mechanisms enabled
  - [ ] Trigger effectiveness monitoring established
```

## Usage Examples

**AUTOMATIC ACTIVATION EXAMPLES:**
```yaml
example_scenarios:
  complex_bug_investigation:
    trigger: "Bug affecting 3+ components, unknown root cause"
    activation: "zen_debug → sequential_thinking → zen_consensus"
    agents: ["backend-developer", "quality-specialist"]
    
  architecture_design:
    trigger: "System design with 5+ components, 3+ integrations"
    activation: "sequential_thinking → zen_analyze → zen_consensus → zen_planner"
    agents: ["architect", "backend-developer", "quality-specialist"]
    
  security_hardening:
    trigger: "OWASP vulnerability detected, PII data involved"
    activation: "zen_secaudit → zen_consensus → zen_planner → zen_testgen"
    agents: ["quality-specialist", "backend-developer", "devops-engineer"]
    
  performance_optimization:
    trigger: "Response time > 500ms, 3+ bottlenecks identified"
    activation: "zen_analyze → zen_tracer → sequential_thinking → zen_refactor"
    agents: ["quality-specialist", "backend-developer", "data-engineer"]
```