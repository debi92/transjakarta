Transjakarta Transactions (April 2023) EDA & Analysis

Transjakarta in one of popular mean of transportation that operated in Jakarta since 2004. The buses operate in dedicated lanes also known as busways, with ticket prices subsidized by the regional goverment. By the end of 2022, Transjakarta has operated 3.751 bus and 230 routes. Currently, when the pandemic has subsided, the DKI Jakarta Provincial Government (Pemprov) has integrated several modes of transportation, namely Transjakarta, Light Rapid Transit (LRT), Electric Rail Train (KRL), and Integrated Mass Rapid Transit (MRT).
 
The main objective of this project is to find insights and alternative solutions by looking at TJ customers behaviour so Jakarta can provide safe and efficient public transportations to Jakarta's citizen. To achieve that goal, this project will perform Explorative Data Analysis on Transjakarta customer data (April 2023).

Consist of 22 column and 37900 rows

transID: Unique transaction id for every transaction
payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
payCardBank: Customers card bank issuer name
payCardName: Customers name that is embedded in the card.
payCardSex: Customers sex that is embedded in the card
payCardBirthDate: Customers birth year
corridorID: Corridor ID / Route ID as key for route grouping.
corridorName: Corridor Name / Route Name contains Start and Finish for each route.
direction: 0 for Go, 1 for Back. Direction of the route.
tapInStops: Tap In (entrance) Stops ID for identifying stops name
tapInStopsName: Tap In (entrance) Stops Name where customers tap in.
tapInStopsLat: Latitude of Tap In Stops
tapInStopsLon: Longitude of Tap In Stops
stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
tapInTime: Time of tap in. Date and time
tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
tapOutStopsName: Tap out (exit) Stops Name where customers tap out.
tapOutStopsLat: Latitude of Tap Out Stops
tapOutStopsLon: Longitude of Tap Out Stops
stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
tapOutTime: Time of tap out. Date and time
payAmount: The number of what customers pay. Some are free. Some not.
