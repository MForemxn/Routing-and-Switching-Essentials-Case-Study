# Routing and Switching Essentials Case Study - GROUP 1

## Project Overview
This repository contains the Packet Tracer configuration files for our enterprise network design project. The network integrates static routing, OSPF, VLAN segmentation, DHCP, NAT/PAT, and wireless connectivity.

**Start Date:** March 31, 2025  
**Due Date:** May 1, 2025

## Repository Structure
```
/
├── packet_tracer/        # Main Packet Tracer files 
├── documentation/        # Project documentation and diagrams
├── configs/              # Exported device configurations
└── README.md             # This file
```

## Collaboration Guidelines

### Pull Request Process
1. **Create a Branch**
   ```
   git checkout -b <task-name>-<your-name>
   ```

2. **Make Your Changes**
   - Work only during your assigned timeslot
   - Commit frequently with detailed messages
   ```
   git commit -m "Detailed description of what you changed"
   ```

3. **Push Your Branch**
   ```
   git push origin <task-name>-<your-name>
   ```

4. **Create a Pull Request**
   - Go to the repository on GitHub
   - Click "New Pull Request"
   - Select your branch
   - Add detailed description of your changes
   - Request a review from the next team member

5. **Review Process**
   - The next person in the schedule will review your PR
   - If changes are needed, address them
   - Once approved, the PR will be merged

### Conflict Resolution
If merge conflicts occur:
1. First attempt to resolve via GitHub interface
2. For complex conflicts, the team will meet to resolve together
3. Document any network design changes resulting from conflict resolution

## Work Schedule

| Date Range | Task | Assigned To | Prerequisites |
|------------|------|-------------|---------------|
| Mar 31 - Apr 2 | VLSM IP Addressing | Mason | None |
| Apr 3 - Apr 5 | Construct the Network | Takunda | IP Addressing |
| Apr 6 - Apr 8 | Configure Static Routing | Noah | Network Construction |
| Apr 9 - Apr 11 | Configure OSPF | Saihaj | Static Routing |
| Apr 12 - Apr 14 | Configure VLAN and Inter-VLAN Routing | Alexander | Network Construction |
| Apr 15 - Apr 17 | Configure NAT | Mason | Static Routing |
| Apr 18 - Apr 20 | Configure ACLs | Takunda | NAT Configuration |
| Apr 21 - Apr 23 | Configure DHCP | Noah | VLAN Configuration |
| Apr 24 - Apr 26 | Configure WLAN | Saihaj | DHCP Configuration |
| Apr 27 - Apr 29 | Test Connectivity and Troubleshoot | Alexander | All configurations |
| Apr 30 - May 1 | Final Review and Documentation | All Members | All tasks |

## Access Rules
1. Only work on the project during your assigned time slots
2. If you need emergency access outside your slot, notify the team via group chat
3. Document all changes thoroughly in commit messages and PR descriptions
4. After completing your task, update the task status in the project board

## Task Details

### Week 1: Planning & Addressing (Mar 31 - Apr 5)
- Review project requirements
- Design VLSM IP addressing
- Document IP addressing scheme

### Week 2: Network Construction & Basic Routing (Apr 6 - Apr 11)
- Configure device names and basic settings
- Implement physical topology
- Setup initial routing

### Week 3: VLANs & Advanced Routing (Apr 12 - Apr 17)
- Configure VLANs and trunking
- Setup inter-VLAN routing
- Implement NAT/PAT

### Week 4: Services Configuration (Apr 18 - Apr 23)
- Configure ACLs for security
- Implement DHCP services
- Setup wireless network

### Week 5: Testing & Finalization (Apr 24 - May 1)
- Test connectivity between all network segments
- Troubleshoot any issues
- Complete documentation
- Final review of the project

## Report Responsibilities

| Section | Responsible | Due Date |
|---------|-------------|----------|
| Problem Statement | Mason | Apr 10 |
| Project Task Allocation | Takunda | Apr 10 |
| Project Weekly Schedule | Noah | Apr 10 |
| Design and Implementation | Saihaj | Apr 25 |
| Discussions and Troubleshooting | Alexander | Apr 29 |
| Final Assembly | All | May 1 |

## Best Practices
- Save frequent versions of the Packet Tracer file
- Export device configurations after significant changes
- Take screenshots of working configurations
- Document any deviations from the original plan
- Update this README as needed with new information
