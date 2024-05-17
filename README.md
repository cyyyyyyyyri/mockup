<mxfile host="app.diagrams.net">
  <diagram name="Mockup Sistema de Gestión de Eventos">
    <mxGraphModel dx="1390" dy="820" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        
        <!-- Encabezado -->
        <mxCell id="encabezado" value="" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#f8f8f8;strokeColor=#d6d6d6;" vertex="1" parent="1">
          <mxGeometry x="0" y="0" width="800" height="60" as="geometry" />
        </mxCell>
        <mxCell id="logo" value="Logo Hotel" style="shape=rect;whiteSpace=wrap;html=1;" vertex="1" parent="encabezado">
          <mxGeometry x="20" y="15" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="menu" value="Inicio | Habitaciones | Restaurantes | Eventos | Contacto" style="shape=rect;whiteSpace=wrap;html=1;" vertex="1" parent="encabezado">
          <mxGeometry x="140" y="15" width="600" height="30" as="geometry" />
        </mxCell>

        <!-- Gestión de Eventos -->
        <mxCell id="tituloGestionEventos" value="Gestión de Eventos" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#D9EAD3;strokeColor=#6AA84F;fontSize=24;" vertex="1" parent="1">
          <mxGeometry x="20" y="80" width="760" height="50" as="geometry" />
        </mxCell>
        <mxCell id="botonAgregarEvento" value="Agregar Nuevo Evento" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#EAD1DC;strokeColor=#CC0000;fontSize=16;" vertex="1" parent="1">
          <mxGeometry x="20" y="140" width="200" height="30" as="geometry" />
        </mxCell>

        <!-- Tabla de Eventos -->
        <mxCell id="tablaEventos" value="" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="180" width="760" height="150" as="geometry" />
        </mxCell>
        <mxCell id="columnaNombre" value="Nombre Evento" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#f0f0f0;strokeColor=#d6d6d6;" vertex="1" parent="tablaEventos">
          <mxGeometry x="0" y="0" width="200" height="30" as="geometry" />
        </mxCell>
        <mxCell id="columnaCapacidad" value="Capacidad" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#f0f0f0;strokeColor=#d6d6d6;" vertex="1" parent="tablaEventos">
          <mxGeometry x="200" y="0" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="columnaDisponibilidad" value="Disponibilidad" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#f0f0f0;strokeColor=#d6d6d6;" vertex="1" parent="tablaEventos">
          <mxGeometry x="300" y="0" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="columnaPrecio" value="Precio" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#f0f0f0;strokeColor=#d6d6d6;" vertex="1" parent="tablaEventos">
          <mxGeometry x="400" y="0" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="columnaAcciones" value="Acciones" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#f0f0f0;strokeColor=#d6d6d6;" vertex="1" parent="tablaEventos">
          <mxGeometry x="500" y="0" width="100" height="30" as="geometry" />
        </mxCell>

        <!-- Fila Ejemplo -->
        <mxCell id="filaEjemplo" value="" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#d6d6d6;" vertex="1" parent="tablaEventos">
          <mxGeometry x="0" y="30" width="760" height="30" as="geometry" />
        </mxCell>
        <mxCell id="nombreEventoEjemplo" value="Conferencia de Verano" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="filaEjemplo">
          <mxGeometry x="0" y="0" width="200" height="30" as="geometry" />
        </mxCell>
        <mxCell id="capacidadEjemplo" value="200" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="filaEjemplo">
          <mxGeometry x="200" y="0" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="disponibilidadEjemplo" value="Disponible" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="filaEjemplo">
          <mxGeometry x="300" y="0" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="precioEjemplo" value="$1000" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="filaEjemplo">
          <mxGeometry x="400" y="0" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="accionesEjemplo" value="[Editar] [Eliminar]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="filaEjemplo">
          <mxGeometry x="500" y="0" width="100" height="30" as="geometry" />
        </mxCell>

        <!-- Formulario de Agregar/Editar Evento -->
        <mxCell id="tituloFormulario" value="Formulario de Agregar/Editar Evento" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#D9EAD3;strokeColor=#6AA84F;fontSize=18;" vertex="1" parent="1">
          <mxGeometry x="20" y="340" width="760" height="40" as="geometry" />
        </mxCell>
        <mxCell id="campoNombreEvento" value="Nombre del Evento: [_________________________]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="390" width="300" height="30" as="geometry" />
        </mxCell>
        <mxCell id="campoCapacidad" value="Capacidad: [______]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="430" width="200" height="30" as="geometry" />
        </mxCell>
        <mxCell id="campoDisponibilidad" value="Disponibilidad: [X]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="470" width="200" height="30" as="geometry" />
        </mxCell>
        <mxCell id="campoPrecio" value="Precio de Arriendo: [$______]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="510" width="300" height="30" as="geometry" />
        </mxCell>
        <mxCell id="botonesFormulario" value="[Guardar] [Cancelar]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="550" width="300" height="30" as="geometry" />
        </mxCell>

        <!-- Reservar Evento -->
        <mxCell id="tituloReservarEvento" value="Reservar Evento" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#D9EAD3;strokeColor=#6AA84F;fontSize=18;" vertex="1" parent="1">
          <mxGeometry x="20" y="600" width="760" height="40" as="geometry" />
        </mxCell>
        <mxCell id="campoSeleccionarEvento" value="Seleccionar Evento: [_________________________]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="650" width="300" height="30" as="geometry" />
        </mxCell>
        <mxCell id="campoFechaReserva" value="Fecha de Reserva: [____________]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="690" width="300" height="30" as="geometry" />
        </mxCell>
        <mxCell id="campoInstitucion" value="Institución: [_________________________]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="730" width="300" height="30" as="geometry" />
        </mxCell>
        <mxCell id="campoContacto" value="Contacto: [_________________________]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="770" width="300" height="30" as="geometry" />
        </mxCell>
        <mxCell id="botonReservar" value="[Reservar]" style="shape=rect;whiteSpace=wrap;html=1;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="20" y="810" width="300" height="30" as="geometry" />
        </mxCell>
        
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
