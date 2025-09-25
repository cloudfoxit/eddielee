# Eddie Lee

**Systems-savvy strategist. Tech-first operator. Builder of Cloudfox.**

I blend financial precision with technical fluency to simplify complex systems for property businesses. From stitching together HubSpot, Xero, Stripe, and PMS platforms, to designing automation pipelines and multi-layer reports, I make data work harder and processes run smoother.

**Tools I Use:** Python, Supabase, Power Query, Canva, HubSpot, and clean processes.

**Approach:** Scalable systems. Measurable value. Quiet leadership.

---

**Current Focus:**
- Rolling out Grand Slam Offers for PBSA & Build-to-Rent  
- Building a SaaS platform for landlord analytics  
- Supporting implementation and integrations across systems  
- Growing the Cloudfox community for ops professionals in property  
- Personal branding on LinkedIn

---
# University of Brighton → Every Student Booking Processes

## Current vs Ideal Process Overview

The diagram below shows the **current processes** as they operate today and the **ideal process** we want to move toward.  
- *Current pre-arrival*: UoB sends daily snapshot files (“check-in reports”), which should only be used for validation of arrivals, not for creating confirmed bookings until the booking start date.  
- *Current in-contract*: UoB sends ad-hoc change files by email (room swaps, late starts/ends), which are manually applied.  
- *Ideal*: UoB sends a complete daily file containing all allocations (confirmed, tentative, cancelled, ended), allowing automation and reconciliation.

```mermaid
flowchart TD
    subgraph Current_Process[Current Process: Pre-arrival allocations]
        A1[University of Brighton\nsends daily snapshot (check-in report)] --> A2[Every Student receives file]
        A2 --> A3[File used only for validation of arrivals\nNOT for creating confirmed bookings]
        A3 --> A4[If booking start date = today\nthen create confirmed booking]
        A2 --> A5[Reports on 18th, 19th, 20th, 21st may differ:\n- Tenant in one room\n- Tenant replaced\n- Tenant removed\n- Completely different allocation]
        A5 --> A4
    end

    subgraph Current_Live[Current Process: In-contract changes]
        B1[University sends ad-hoc file by email] --> B2[File contains:\n- Room swaps\n- Late starts\n- Late ends]
        B2 --> B3[Every Student updates bookings manually]
    end

    subgraph Ideal_Process[Ideal Process (Target)]
        C1[University sends one updated file daily] --> C2[File contains:\n- Active bookings (confirmed/tentative)\n- Cancelled bookings\n- Ended bookings\n- New additions with start/end dates & status]
        C2 --> C3[Every Student system automatically reconciles bookings]
        C3 --> C4[Bookings updated consistently in Concurrent]
    end
```

    
**Links:**
- [Company: Cloudfox Group Ltd](https://cloudfox.it)
- [LinkedIn: @eddlee](https://www.linkedin.com/in/eddlee)
