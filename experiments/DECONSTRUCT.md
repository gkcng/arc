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
lr = CustomSchedule (4K Warmup Steps)
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
lr = CustomSchedule (4K Warmup Steps)
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
		<td>6.3</td>
		<td>2024-03-08</td>
		<td>5x5 Fixed Grid - Move A Pixel To the Right - Full Color Spectrum</td>
		<td>120</td>
		<td>4728</td>
		<td>1052</td>
	</tr>
	<tr>
		<th colspan=2>HyperParams</th>
		<th colspan=4>Epochs/Loss</th>
	</tr>
	<tr><td colspan=2 rowspan=3>
<pre>
batch size = 8
num_layers = 1
d_model = 64 
dff = 256
num_heads = 1 
dropout = 0.1
lr = CustomSchedule (15K Warmup Steps)
</pre>		
	</td><td colspan=4>
Epoch 120 - 15s 25ms/step - loss: 0.0036 - lr: 4.7036e-04 - val_loss: 0.0029
</td>
	</tr>
	<tr><th colspan=4>Results</th></tr>
	<tr><td colspan=4>
<code>
TrainSet: 
<b>Count: 4728, Avg loss: 0.0007, Accuracy: 4208 (0.8900), Stops found: 4728</b>
TestSet: 
Count: 1052, Avg loss: 0.0019, Accuracy: 557 (0.5295), Stops found: 1052
</code>
</td></tr>	
</table>
