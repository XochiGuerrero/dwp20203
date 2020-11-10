<template>
  <ion-card>
    <ion-card-header>
      <ion-card-subtitle>Ventas</ion-card-subtitle>
      <ion-card-title>Productos</ion-card-title>
    </ion-card-header>

    <ion-card-content>
      <div class="container">
	<div class="row">
		<div class="col-xs-8">
			<div class="panel panel-info">
				<div class="panel-heading">
					<div class="panel-title">
						<div class="row">
							<div class="col-xs-6">
								<h5><span class="glyphicon glyphicon-shopping-cart"></span> Carrito de compras</h5>
							</div>
							<div class="col-xs-6">
								<button type="button" class="btn btn-primary btn-sm btn-block">
									<span class="glyphicon glyphicon-share-alt"></span> Seguir comprando
								</button>
							</div>
						</div>
					</div>
				</div>
				<div class="panel-body">
					<div class="row">
						<div class="col-xs-2"><img class="img-responsive" src="https://images-na.ssl-images-amazon.com/images/I/61bdXjiYXqL._AC_UY395_.jpg">
						</div>
						<div class="col-xs-4">
							<h4 class="product-name"><strong>Nombre del producto</strong></h4>
                            <h4><small>Aretes marca Tiffany & Co</small></h4>
                            <h5>Descripcion del producto</h5>
                            <h4><small>Aretes de 24k con Diamantes incrustados</small></h4>
						</div>
						<div class="col-xs-6">
							<div class="col-xs-6 text-right">
								<h6><strong>3200 <span class="text-muted">x</span></strong></h6>
							</div>
							<div class="col-xs-4">
								<input type="text" class="form-control input-sm" value="1">
							</div>
							<div class="col-xs-2">
								<button type="button" class="btn btn-link btn-xs">
									<span class="glyphicon glyphicon-trash"> </span>
								</button>
							</div>
						</div>
					</div>
					<hr>
					<div class="row">
						<div class="col-xs-2"><img class="img-responsive" src="https://www.ecestaticos.com/imagestatic/clipping/b28/ddc/b28ddc8df549b2decc584593931e117f/las-joyas-perdidas-de-la-corona-espanola-y-el-hombre-que-las-rescato.jpg?mtime=1488798216">
						</div>
						<div class="col-xs-4">
							<h4 class="product-name"><strong>Nombre del producto</strong></h4>
                            <h4><small>Collar de esmeraldas</small></h4>
                            <h5>Descripcion del producto</h5>
                            <h4><small>Oro de 14k con esmeraldas</small></h4>
						</div>
						<div class="col-xs-6">
							<div class="col-xs-6 text-right">
								<h6><strong>5000 <span class="text-muted">x</span></strong></h6>
							</div>
							<div class="col-xs-4">
								<input type="text" class="form-control input-sm" value="1">
							</div>
							<div class="col-xs-2">
								<button type="button" class="btn btn-link btn-xs">
									<span class="glyphicon glyphicon-trash"> </span>
								</button>
							</div>
						</div>
					</div>
					<hr>


                      <div class="row">
						<div class="col-xs-2"><img class="img-responsive" src="https://joyas10.top/imagenes/los-mejores-brazaletes-de-oro.png">
						</div>
						<div class="col-xs-4">
							<h4 class="product-name"><strong>Nombre del producto</strong></h4>
                            <h4><small>Brazalete marca Cartier</small></h4>
                            <h5>Descripcion del producto</h5>
                            <h4><small>Oro de 24k con zafiros incrustados</small></h4>
						</div>
						<div class="col-xs-6">
							<div class="col-xs-6 text-right">
								<h6><strong>10000 <span class="text-muted">x</span></strong></h6>
							</div>
							<div class="col-xs-4">
								<input type="text" class="form-control input-sm" value="1">
							</div>
							<div class="col-xs-2">
								<button type="button" class="btn btn-link btn-xs">
									<span class="glyphicon glyphicon-trash"> </span>
								</button>
							</div>
						</div>
					</div>
					<hr>


					<div class="row">
						<div class="text-center">
							<div class="col-xs-9">
								<h6 class="text-right">Añadir mas productos</h6>
							</div>
							<div class="col-xs-3">
								<button type="button" class="btn btn-default btn-sm btn-block">
									Añadir
								</button>
							</div>
						</div>
					</div>
				</div>
				<div class="panel-footer">
					<div class="row text-center">
						<div class="col-xs-9">
							<h4 class="text-right">Total <strong>$18200</strong></h4>
						</div>
						<div class="col-xs-3">
							<button type="button" class="btn btn-success btn-block">
								Comprar
							</button>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
    </ion-card-content>
  </ion-card>
</template>


<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Ventas",
  components: {},
});



</script>

