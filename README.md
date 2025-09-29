# Trade-network-analysis

# Spanish Inter-Sector Trade Network Analysis

## Project Overview
Network analysis of trade relationships between economic sectors in Spain using Gephi. This project examines a directed, weighted network representing goods exchange between different industrial sectors.

## Network Characteristics
- **Type**: Directed and weighted network
- **Nodes**: Economic sectors in Spain
- **Edges**: Trade relationships (imports/exports)
- **Weight**: Volume of goods exchanged

## Key Findings

### Centrality Analysis
**Highest Weighted In-Degree**: 
- **Sector C20** (135.50 units)
- *Interpretation*: Largest importer of goods from other Spanish sectors

**Highest Weighted Out-Degree**:
- **Sector C20** (194.12 units)  
- *Interpretation*: Largest exporter of goods to other Spanish sectors

### Top Central Nodes
**By Weighted Degree** (Total trade volume):
1. ESP_C20
2. ESP_C29
3. ESP_C24
4. ESP_C28
5. ESP_C21

**By PageRank** (Influence-based centrality):
1. ESP_Q
2. ESP_F
3. ESP_C28
4. ESP_C21
5. ESP_C29

### Community Structure
- **Number of classes/communities**: 5 clusters
- **Basis for clustering**: Trade patterns, economic relationships, and sector interdependencies

## Technical Insights
- **Centrality measures provide different perspectives**: Weighted degree measures total trade volume, while PageRank identifies influential sectors with broader network connections
- **Sector C20 dominates** both import and export activities
- **Community detection reveals** natural economic groupings based on trade relationships


## Tools Used
- **Gephi** - Network analysis and visualization
- **Statistical analysis** - Centrality measures and community detection

## Economic Interpretation
The analysis reveals key structural patterns in Spain's internal trade network, identifying central sectors that drive economic activity and natural clusters of interdependent industries.


