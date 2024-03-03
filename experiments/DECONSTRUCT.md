<table width="100%">
	<tr>
		<th>No.</th> 
		<th>Date</th> 		
		<th>Task</th>
		<th>TaskSet Size</th>
		<th>Training Rows</th>
		<th>Test Rows</th>
	</tr>
	<tr>
		<td>6.1</td>
		<td>2024-03-02</td>
		<td>5x5 Fixed Grid - Move A Pixel To the Right</td>
		<td>50</td>
		<td>224</td>
		<td>51</td>
	</tr>
	<tr>
		<th colspan=2>HyperParams</th>
		<th colspan=4>Epochs/Loss</th>
	</tr>
	<tr><td colspan=2 rowspan=3>
<pre>
batch size = 64
num_layers = 1
d_model = 32 
dff = 128
num_heads = 1 
dropout = 0.1
lr = 1e-03
lr_patience = 8
lr_factor = 0.8
</pre>
	</td>
	<td colspan=4>Epoch: 300 - 0.16 secs - loss: 0.0022</td>
	</tr>
	<tr><th colspan=4>Results</th></tr>
	<tr><td colspan=4>
<code>TrainSet: 
Count: 224, Avg loss: 0.0008, Accuracy: 144 (0.6429), Stops found: 224

TestSet: 
Count: 51, Avg loss: 0.0488, Accuracy: 0 (0.0000), Stops found: 51</code>
    </td></tr>	
</table>

<table>
	<tr>
		<th>No.</th> 
		<th>Date</th> 
		<th>Task</th>
		<th>TaskSet Size</th>
		<th>Training Rows</th>
		<th>Test Rows</th>
	</tr>
	<tr>
		<td>6.2</td>
		<td>2024-03-02</td>
		<td>5x5 Fixed Grid - Move A Pixel To the Right</td>
		<td>50</td>
		<td>224</td>
		<td>51</td>
	</tr>
	<tr>
		<th colspan=2>HyperParams</th>
		<th colspan=4>Epochs/Loss</th>
	</tr>
	<tr><td colspan=2 rowspan=3>
<pre>
batch size = 4
num_layers = 1
d_model = 32 
dff = 128
num_heads = 1 
dropout = 0.1
lr = 1e-03
lr_patience = 8
lr_factor = 0.8
</pre>		
	</td><td colspan=4>
Epoch: 300 - 0.44 secs - loss: 0.0003 (reached around 220-240)

Epoch: 300 - 0.59 secs - loss: 0.0006 (reached around 160)
</td>
	</tr>
	<tr><th colspan=4>Results</th></tr>
	<tr><td colspan=4>
<code>Run 1:
TrainSet: 
<b>Count: 224, Avg loss: 0.0000, Accuracy: 224 (1.0000), Stops found: 224</b>
TestSet: 
Count: 51, Avg loss: 0.0055, Accuracy: 0 (0.0000), Stops found: 51

Run 2:
TrainSet: 
<b>Count: 224, Avg loss: 0.0001, Accuracy: 224 (1.0000), Stops found: 224</b>
TestSet: 
Count: 51, Avg loss: 0.0639, Accuracy: 0 (0.0000), Stops found: 51</code>
</td></tr>	
</table>
