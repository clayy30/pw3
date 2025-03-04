<mxfile host="app.diagrams.net" modified="2024-03-03T21:43:00.000Z" agent="Mozilla/5.0" version="21.7.5" etag="powerwall_eng_grade">
  <diagram id="powerwall_detailed_SLD" name="Powerwall Engineering SLD">
    <mxGraphModel dx="1500" dy="1100" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1100" pageHeight="850" background="#ffffff">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        
        <!-- Utility Connection -->
        <mxCell id="utility_symbol" value="" style="shape=mxgraph.electrical.transmission.utility_pole;aspect=fixed;" vertex="1" parent="1">
          <mxGeometry x="100" y="40" width="50" height="50" as="geometry"/>
        </mxCell>
        
        <!-- Georgia Power POI -->
        <mxCell id="poi_label" value="Point of Interconnection&#xa;Georgia Power&#xa;120/240V 1Φ 3W&#xa;SCCR: 10kA" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="160" y="30" width="200" height="70" as="geometry"/>
        </mxCell>

        <!-- Revenue Meter -->
        <mxCell id="meter" value="Form 2S Smart Meter&#xa;Bi-Directional&#xa;CL200" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="120" width="160" height="60" as="geometry"/>
        </mxCell>

        <!-- Main Service Disconnect -->
        <mxCell id="main_disconnect" value="200A Main Service Disconnect&#xa;NEMA 3R&#xa;22kAIC" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="220" width="160" height="60" as="geometry"/>
        </mxCell>

        <!-- Main Panel -->
        <mxCell id="main_panel" value="Main Service Panel&#xa;200A MLO&#xa;120/240V 1Φ&#xa;42 spaces" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="320" width="160" height="80" as="geometry"/>
        </mxCell>

        <!-- Tesla Gateway -->
        <mxCell id="gateway" value="Tesla Gateway 3&#xa;200A Continuous&#xa;w/ATS&#xa;NEMA 3R" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="400" y="320" width="160" height="80" as="geometry"/>
        </mxCell>

        <!-- Powerwall -->
        <mxCell id="powerwall" value="Tesla Powerwall 3&#xa;9.6kW / 25.6kWh&#xa;100A Continuous&#xa;NEMA 3R" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="700" y="320" width="160" height="80" as="geometry"/>
        </mxCell>

        <!-- Backup Load Center -->
        <mxCell id="backup_panel" value="Backup Load Center&#xa;200A MLO&#xa;120/240V 1Φ&#xa;30 spaces" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="400" y="440" width="160" height="80" as="geometry"/>
        </mxCell>

        <!-- Wire Specifications -->
        <mxCell id="main_service_conductors" value="2/0 AWG Cu THWN-2&#xa;In 2" EMT&#xa;L1, L2, N, GND" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="270" y="230" width="150" height="50" as="geometry"/>
        </mxCell>

        <!-- Powerwall Connection -->
        <mxCell id="powerwall_conductors" value="4 AWG Cu THWN-2&#xa;In 1.5" EMT&#xa;L1, L2, N, GND" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="570" y="330" width="120" height="50" as="geometry"/>
        </mxCell>

        <!-- CT Specifications -->
        <mxCell id="ct_specs" value="CTs: 200A Split Core&#xa;Revenue Grade&#xa;0.5% Accuracy" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="400" y="270" width="150" height="50" as="geometry"/>
        </mxCell>

        <!-- Grounding Details -->
        <mxCell id="grounding" value="Grounding Electrode System:&#xa;#4 AWG Cu to Ground Rods&#xa;2x 8' Cu Ground Rods&#xa;10' Separation" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="100" y="520" width="200" height="70" as="geometry"/>
        </mxCell>

        <!-- SPD -->
        <mxCell id="spd" value="Type 1 SPD&#xa;50kA per phase" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="270" y="320" width="120" height="40" as="geometry"/>
        </mxCell>

        <!-- Rapid Shutdown -->
        <mxCell id="rapid_shutdown" value="Rapid Shutdown System&#xa;NEC 2020 Compliant" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="700" y="270" width="160" height="40" as="geometry"/>
        </mxCell>

        <!-- Notes Section -->
        <mxCell id="notes" value="NOTES:&#xa;1. All work to comply with NEC 2020 and Georgia Power requirements&#xa;2. All outdoor equipment NEMA 3R rated minimum&#xa;3. System includes automatic transfer switching&#xa;4. All conductors copper, 90°C rated&#xa;5. Equipment grounding conductors sized per NEC 250.122&#xa;6. Surge protection meets NEC 230.67&#xa;7. Gateway includes internet connection for monitoring&#xa;8. System rated for 100A continuous backup power" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="100" y="600" width="800" height="150" as="geometry"/>
        </mxCell>

        <!-- Title Block -->
        <mxCell id="title_block" value="TESLA POWERWALL 3 SINGLE LINE DIAGRAM&#xa;WITH GATEWAY 3 AND WHOLE HOME BACKUP&#xa;GEORGIA POWER INTERCONNECTION&#xa;&#xa;Design Voltage: 120/240V 1Φ&#xa;Main Service: 200A&#xa;Backup Capacity: 9.6kW / 25.6kWh&#xa;System Compliance: NEC 2020, GA Power" style="text;strokeColor=default;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;" vertex="1" parent="1">
          <mxGeometry x="700" y="40" width="300" height="160" as="geometry"/>
        </mxCell>

        <!-- Connections -->
        <!-- Add appropriate connection lines between components -->
        
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>

