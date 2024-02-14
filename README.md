<div *ngFor="let product of products">
  <img [src]="product.image" alt="{{product.name}}">
  <h3>{{product.name}}</h3>
  <p>Price: {{product.price}}</p>
  <button (click)="addToCart(product)">Add to Cart</button>
</div>
