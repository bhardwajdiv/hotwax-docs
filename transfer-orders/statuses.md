# Statuses & Lifecycle

Transfer Order statuses in HotWax OMS track inventory 
movement between facilities at every stage.

## Transfer Order Statuses

### Pending Receipt
The Transfer Order has been created and inventory is 
awaiting receipt at the destination facility.

### Shipped
Inventory has been packed and dispatched from the 
source facility. It is currently in transit.

### Completed
Inventory has been successfully received at the 
destination facility. The transfer is closed.

## Status Lifecycle Flow

Pending Receipt → Shipped → Completed

## Key Notes
- A Transfer Order cannot skip statuses
- Each status change is logged with a timestamp
- Only authorized staff can update Transfer Order statuses
