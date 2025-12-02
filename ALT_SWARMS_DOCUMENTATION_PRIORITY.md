# Alt Swarms Documentation Priority

## Recommended Documentation Strategy

### **Tier 1: High Priority - Core Practical Patterns** ⭐⭐⭐

These are the most practical and commonly used patterns that should be documented first:

1. **LinearSwarm** ⭐⭐⭐
   - **Why**: Most intuitive pattern - sequential processing
   - **Use Case**: Simple task pipelines, step-by-step workflows
   - **Complexity**: Low
   - **Documentation Priority**: **HIGHEST**

2. **CircularSwarm** ⭐⭐⭐
   - **Why**: Simple circular pattern, easy to understand
   - **Use Case**: Round-robin task distribution, iterative refinement
   - **Complexity**: Low
   - **Documentation Priority**: **HIGHEST**

3. **StarSwarm** ⭐⭐⭐
   - **Why**: Central coordination pattern, very practical
   - **Use Case**: Central agent coordinates others, hierarchical workflows
   - **Complexity**: Medium
   - **Documentation Priority**: **HIGHEST**

4. **MeshSwarm** ⭐⭐⭐
   - **Why**: Random task distribution, good for load balancing
   - **Use Case**: Parallel processing, task queue management
   - **Complexity**: Medium
   - **Documentation Priority**: **HIGHEST**

### **Tier 2: Medium Priority - Hierarchical & Communication Patterns** ⭐⭐

5. **PyramidSwarm** ⭐⭐
   - **Why**: Hierarchical structure, useful for organizational patterns
   - **Use Case**: Multi-level task processing, organizational hierarchies
   - **Complexity**: Medium-High
   - **Documentation Priority**: **MEDIUM**

6. **OneToOne** (Communication Pattern) ⭐⭐
   - **Why**: Basic communication pattern, foundation for others
   - **Use Case**: Two-agent collaboration, simple exchanges
   - **Complexity**: Low
   - **Documentation Priority**: **MEDIUM**

7. **Broadcast** (Communication Pattern) ⭐⭐
   - **Why**: One-to-many communication, very common pattern
   - **Use Case**: Announcements, distributing tasks to multiple agents
   - **Complexity**: Low
   - **Documentation Priority**: **MEDIUM**

### **Tier 3: Lower Priority - Mathematical Patterns** ⭐

These can be grouped together in a single "Mathematical Pattern Swarms" document:

8. **FibonacciSwarm** ⭐
   - **Why**: Mathematical curiosity, less practical
   - **Use Case**: Specialized mathematical task distribution
   - **Complexity**: Medium
   - **Documentation Priority**: **LOW** (group with others)

9. **PrimeSwarm** ⭐
   - **Why**: Mathematical pattern, limited practical use
   - **Use Case**: Specialized task distribution based on prime indices
   - **Complexity**: Medium
   - **Documentation Priority**: **LOW** (group with others)

10. **PowerSwarm** ⭐
    - **Why**: Power-of-2 pattern, some practical applications
    - **Use Case**: Binary tree-like task distribution
    - **Complexity**: Medium
    - **Documentation Priority**: **LOW** (group with others)

11. **LogSwarm** ⭐
    - **Why**: Logarithmic pattern, specialized use
    - **Use Case**: Logarithmic task distribution
    - **Complexity**: Medium
    - **Documentation Priority**: **LOW** (group with others)

12. **ExponentialSwarm** ⭐
    - **Why**: Exponential pattern, specialized use
    - **Use Case**: Exponential task distribution
    - **Complexity**: Medium
    - **Documentation Priority**: **LOW** (group with others)

13. **GeometricSwarm** ⭐
    - **Why**: Geometric progression, specialized use
    - **Use Case**: Geometric task distribution
    - **Complexity**: Medium
    - **Documentation Priority**: **LOW** (group with others)

14. **HarmonicSwarm** ⭐
    - **Why**: Harmonic progression, specialized use
    - **Use Case**: Harmonic task distribution
    - **Complexity**: Medium
    - **Documentation Priority**: **LOW** (group with others)

15. **StaircaseSwarm** ⭐
    - **Why**: Step pattern, less common
    - **Use Case**: Step-like task distribution
    - **Complexity**: Medium
    - **Documentation Priority**: **LOW** (group with others)

16. **SigmoidSwarm** ⭐
    - **Why**: Sigmoid distribution, specialized use
    - **Use Case**: S-curve task distribution
    - **Complexity**: Medium-High
    - **Documentation Priority**: **LOW** (group with others)

17. **SinusoidalSwarm** ⭐
    - **Why**: Sinusoidal distribution, specialized use
    - **Use Case**: Wave-like task distribution
    - **Complexity**: Medium-High
    - **Documentation Priority**: **LOW** (group with others)

18. **OneToThree** (Communication Pattern) ⭐
    - **Why**: Specific pattern, less flexible than Broadcast
    - **Use Case**: Specific three-receiver scenarios
    - **Complexity**: Low
    - **Documentation Priority**: **LOW**

## Recommended Documentation Plan

### Phase 1: Core Patterns (Start Here) ✅
Create individual documentation files for:
1. `linear_swarm.md`
2. `circular_swarm.md`
3. `star_swarm.md`
4. `mesh_swarm.md`

### Phase 2: Hierarchical & Communication
5. `pyramid_swarm.md`
6. `communication_patterns.md` (covers OneToOne, Broadcast, OneToThree)

### Phase 3: Mathematical Patterns (Single Document)
7. `mathematical_pattern_swarms.md` (covers all 9 mathematical patterns in one doc)

## Documentation Structure Recommendation

For each swarm, include:
- **Overview**: What the swarm does
- **Pattern Description**: How agents are organized/selected
- **Use Cases**: When to use this pattern
- **Code Example**: Basic usage
- **Parameters**: Constructor/function parameters
- **Advantages/Disadvantages**: Trade-offs
- **Comparison**: How it differs from similar patterns

## Summary

**Start with these 4 swarms:**
1. LinearSwarm
2. CircularSwarm  
3. StarSwarm
4. MeshSwarm

These cover the most practical use cases and will provide the most value to users. The mathematical patterns can be grouped together later as they're more specialized and less commonly used.

