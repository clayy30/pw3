<mxfile host="app.diagrams.net" modified="2024-03-03T21:48:00.000Z" agent="Mozilla/5.0" version="21.7.5" etag="powerwall_eng_grade_v2">
  <diagram id="powerwall_detailed_SLD" name="Powerwall Engineering SLD">
    <mxGraphModel dx="1500" dy="1100" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1100" pageHeight="850" background="#ffffff">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        
        <!-- Georgia Power Grid -->
        <mxCell id="utility_connection" value="Georgia Power Grid&#xa;120/240V 1Φ 3W&#xa;Service Entrance&#xa;SCCR: 10kA&#xa;Available Fault Current: 10kA" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f5f5f5;" vertex="1" parent="1">
          <mxGeometry x="400" y="40" width="200" height="80" as="geometry"/>
        </mxCell>

        <!-- Service Conductors -->
        <mxCell id="service_conductors" value="2/0 AWG Cu THWN-2 in 2" EMT&#xa;L1, L2: 2/0 AWG&#xa;Neutral: 2/0 AWG&#xa;Ground: #4 AWG Cu&#xa;Conduit Fill: 40% max&#xa;Temp Rating: 90°C&#xa;Voltage Drop: <1%" style="text;align=left;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="610" y="120" width="200" height="100" as="geometry"/>
        </mxCell>

        <!-- Revenue Meter -->
        <mxCell id="meter" value="Form 2S Smart Meter&#xa;Bi-Directional&#xa;CL200, 240V&#xa;Georgia Power Approved&#xa;Revenue Grade&#xa;0.5% Accuracy Class&#xa;ANSI C12.20" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f5f5f5;" vertex="1" parent="1">
          <mxGeometry x="400" y="160" width="200" height="100" as="geometry"/>
        </mxCell>

        <!-- Main Service Panel -->
        <mxCell id="main_panel" value="200A Main Service Panel&#xa;MLO Configuration&#xa;120/240V 1Φ&#xa;22kAIC Rating&#xa;NEMA 3R Enclosure&#xa;42 Circuit Spaces&#xa;Copper Bus Rated 200A&#xa;Integrated Main Breaker&#xa;SPD Type 1 (50kA/phase)" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f5f5f5;" vertex="1" parent="1">
          <mxGeometry x="400" y="300" width="200" height="140" as="geometry"/>
        </mxCell>

        <!-- Tesla Gateway -->
        <mxCell id="gateway" value="Tesla Gateway 3&#xa;200A Continuous Rating&#xa;NEMA 3R Enclosure&#xa;Integrated ATS&#xa;Self-powered&#xa;WiFi/Ethernet Enabled&#xa;Revenue Grade CTs&#xa;Rapid Shutdown Compliant&#xa;UL 1741 Listed&#xa;IEEE 2030.5 Compliant" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f5f5f5;" vertex="1" parent="1">
          <mxGeometry x="400" y="480" width="200" height="160" as="geometry"/>
        </mxCell>

        <!-- Powerwall -->
        <mxCell id="powerwall" value="Tesla Powerwall 3&#xa;9.6kW / 25.6kWh&#xa;100A Continuous&#xa;NEMA 3R Rated&#xa;Operating Temp: -4°F to 122°F&#xa;Round Trip Efficiency: 92.5%&#xa;Backup Inverter: 9.6kW&#xa;Voltage Range: 220-250V&#xa;Frequency: 60Hz&#xa;Power Factor: 1.0" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f5f5f5;" vertex="1" parent="1">
          <mxGeometry x="700" y="480" width="200" height="160" as="geometry"/>
        </mxCell>

        <!-- Powerwall Connection -->
        <mxCell id="powerwall_connection" value="4 AWG Cu THWN-2 in 1.5" EMT&#xa;L1, L2: 4 AWG&#xa;Neutral: 4 AWG&#xa;Ground: 8 AWG Cu&#xa;Conduit Fill: 40% max&#xa;Temp Rating: 90°C&#xa;Voltage Drop: <1%" style="text;align=left;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="610" y="650" width="200" height="100" as="geometry"/>
        </mxCell>

        <!-- Backup Loads -->
        <mxCell id="backup_loads" value="Whole Home Loads&#xa;200A Max Transfer&#xa;Backed Up Circuits:&#xa;- HVAC: 30A 240V&#xa;- Well Pump: 20A 240V&#xa;- Refrigerator: 20A 120V&#xa;- Critical Lighting&#xa;- Security System&#xa;Total Connected Load: 160A" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f5f5f5;" vertex="1" parent="1">
          <mxGeometry x="400" y="680" width="200" height="140" as="geometry"/>
        </mxCell>

        <!-- Grounding System -->
        <mxCell id="grounding" value="Grounding System:&#xa;- (2) 8' Copper Ground Rods&#xa;- 10' Minimum Separation&#xa;- #4 AWG Cu Ground Wire&#xa;- Acorn Clamps&#xa;- Ground Resistance <25 Ohms&#xa;- Supplemental Ground Ring&#xa;- Ground Test Well" style="text;align=left;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="100" y="680" width="200" height="120" as="geometry"/>
        </mxCell>

        <!-- Title Block -->
        <mxCell id="title_block" value="TESLA POWERWALL 3 SINGLE-LINE DIAGRAM&#xa;GEORGIA POWER INTERCONNECTION&#xa;&#xa;Project: Whole Home Backup Installation&#xa;Location: Georgia&#xa;Drawing: SLD-001&#xa;Rev: A&#xa;Date: 03/03/2024&#xa;Drawn By: TeslaPro&#xa;PE Stamp Location: [    ]" style="text;strokeColor=default;fillColor=none;align=left;verticalAlign=top;" vertex="1" parent="1">
          <mxGeometry x="100" y="40" width="250" height="160" as="geometry"/>
        </mxCell>

        <!-- Notes Section -->
        <mxCell id="notes" value="NOTES:&#xa;1. All work to comply with N
