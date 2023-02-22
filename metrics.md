## Chain Metrics
* `lnd_chain_block_height`: best block height from lnd
* `lnd_chain_block_timestamp`: best block timestamp from lnd
* `lnd_synced_to_chain`: whether lnd is synced to chain
* `lnd_synced_to_graph`: whether lnd is synced to graph

## Channel Metrics
* `lnd_channels_open_balance_sat`: total balance of channels in satoshis
* `lnd_channels_pending_balance_sat`: total balance of all pending channels in satoshis
* `lnd_channels_bandwidth_incoming_sat`: total available incoming channel bandwidth within this channel
* `lnd_channels_bandwidth_outgoing_sat`: total available outgoing channel bandwidth within this channel
* `lnd_channels_pending_htlc_count`: total number of pending active HTLCs within this channel
* `lnd_channels_active_total`: total number of active channels
* `lnd_channels_inactive_total`: total number of inactive channels
* `lnd_channels_pending_total`: total number of inactive channels
* `lnd_channels_csv_delay`: CSV delay in relative blocks for this channel
* `lnd_channels_unsettled_balance`: unsettled balance in this channel
* `lnd_channels_fee_per_kw`: required number of sat per kiloweight that the requester will pay for the funding and commitment transaction
* `lnd_channels_commit_weight`: weight of the commitment transaction
* `lnd_channels_commit_fee`: weight of the commitment transaction
* `lnd_channels_sent_sat`: total number of satoshis we’ve sent within this channel
* `lnd_channels_received_sat`: total number of satoshis we’ve received within this channel
* `lnd_channels_updates_count`: total number of updates conducted within this channel
  
## Graph Metrics
* `lnd_graph_edges_count`: total number of edges in the graph
* `lnd_graph_nodes_count`: total number of nodes in the graph
* `lnd_graph_outdegree_avg`: the avg out degreee of nodes in the network
* `lnd_graph_outdegree_max`: the max out degree of nodes in the network
* `lnd_graph_chan_capacity_sat`: the total capacity of the network in satoshis
* `lnd_graph_chan_size_avg`: the avg channel size in the network
* `lnd_graph_chan_size_min`: the smallest channel in the network
* `lnd_graph_chan_size_max`: the largest channel in the network
* `lnd_graph_chan_size_median`: the median channel size in the network
* `lnd_graph_timelock_delta_{min, max, avg, median}`: the min/max/avg/median time lock delta across all chanenls
* `lnd_graph_min_htlc_msat_{min, max, avg, median}`: the min/max/avg/median min htlc across all channels
* `lnd_graph_fee_base_msat_{min, max, avg, median}`: the min/max/avg/median base fee across all channels
* `lnd_graph_fee_rate_msat_{min, max, avg, median}`: the min/max/avg/median fee rate across all channels
* `lnd_graph_max_htlc_msat_{min, max, avg, median}`: the min/max/avg/median max htlc across all channels
 
## Peer Metrics
* `lnd_peer_count`: total number of peers
* `lnd_peer_ping_time_microsecond`: ping time for this peer in microseconds
* `lnd_peer_sent_sat`: satoshis sent to this peer
* `lnd_peer_recv_sat`: satoshis received from this peer
* `lnd_peer_sent_byte`: bytes transmitted to this peer
* `lnd_peer_recv_byte`: bytes transmitted from this peer
  
  
## Wallet Metrics
* `lnd_utxos_count_confirmed_total`: number of all conf utxos
* `lnd_utxos_count_unconfirmed_total`: number of all unconf utxos
* `lnd_utxos_sizes_min_sat`: smallest UTXO size
* `lnd_utxos_sizes_max_sat`: largest UTXO size
* `lnd_utxos_sizes_avg_sat`: average UTXO size
* `lnd_wallet_balance_confirmed_sat`: confirmed wallet balance
* `lnd_wallet_balance_unconfirmed_sat`: unconfirmed wallet balance
* `lnd_tx_num_confs`: number of confs
