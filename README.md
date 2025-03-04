<mxfile host="app.diagrams.net" modified="2024-01-09T15:42:00.000Z" agent="Mozilla/5.0" version="21.7.5" etag="your_etag">
  <diagram id="powerwall_system" name="Powerwall System">
    <mxGraphModel dx="1050" dy="887" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        
        <!-- Georgia Power Grid -->
        <mxCell id="grid" value="Georgia Power Grid" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="40" width="160" height="60" as="geometry"/>
        </mxCell>
        
        <!-- Form 2S Smart Meter -->
        <mxCell id="meter" value="Form 2S Smart Meter" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="140" width="160" height="60" as="geometry"/>
        </mxCell>
        
        <!-- Main Panel -->
        <mxCell id="panel" value="200A Main Panel" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="240" width="160" height="60" as="geometry"/>
        </mxCell>
        
        <!-- Gateway -->
        <mxCell id="gateway" value="Tesla Gateway 3&#xa;with ATS" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="340" width="160" height="60" as="geometry"/>
        </mxCell>
        
        <!-- Powerwall -->
        <mxCell id="powerwall" value="Powerwall" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="560" y="340" width="160" height="60" as="geometry"/>
        </mxCell>
        
        <!-- Home Loads -->
        <mxCell id="loads" value="Whole Home Loads" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="440" width="160" height="60" as="geometry"/>
        </mxCell>
        
        <!-- Connections -->
        <mxCell id="grid_to_meter" value="" style="endArrow=classic;startArrow=classic;html=1;exitX=0.5;exitY=0;entryX=0.5;entryY=1;" edge="1" parent="1" source="meter" target="grid">
          <mxGeometry width="50" height="50" relative="1" as="geometry"/>
        </mxCell>
        
        <mxCell id="meter_to_panel" value="" style="endArrow=classic;startArrow=classic;html=1;exitX=0.5;exitY=0;entryX=0.5;entryY=1;" edge="1" parent="1" source="panel" target="meter">
          <mxGeometry width="50" height="50" relative="1" as="geometry"/>
        </mxCell>
        
        <mxCell id="panel_to_gateway" value="" style="endArrow=classic;startArrow=classic;html=1;exitX=0.5;exitY=0;entryX=0.5;entryY=1;" edge="1" parent="1" source="gateway" target="panel">
          <mxGeometry width="50" height="50" relative="1" as="geometry"/>
        </mxCell>
        
        <mxCell id="gateway_to_loads" value="" style="endArrow=classic;startArrow=classic;html=1;exitX=0.5;exitY=0;entryX=0.5;entryY=1;" edge="1" parent="1" source="loads" target="gateway">
          <mxGeometry width="50" height="50" relative="1" as="geometry"/>
        </mxCell>
        
        <mxCell id="gateway_to_powerwall" value="" style="endArrow=classic;startArrow=classic;html=1;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="480" y="369.5" as="sourcePoint"/>
            <mxPoint x="560" y="369.5" as="targetPoint"/>
          </mxGeometry>
        </mxCell>
        
        <!-- Wire Labels -->
        <mxCell id="main_wire_label" value="2/0 AWG in EMT" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="400" y="110" width="100" height="20" as="geometry"/>
        </mxCell>
        
        <mxCell id="powerwall_wire_label" value="4 AWG in EMT" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="480" y="340" width="80" height="20" as="geometry"/>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>

