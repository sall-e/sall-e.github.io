{:.no_toc}

# 🔥 Request for TextrolSpeech
<p align="justify">
We have released a demo version containing 500 style descriptions on this page with five style factors: female, high pitch, normal speaking speed, low energy, neutral. You can click <a href="demo_version.txt" download="demo.txt">demo_version</a> to download.
Full textrolspeech dataset download as follows:
<ul>
<li> <a href="https://github.com/jishengpeng/TextrolSpeech">Github Link</a> </li>
</ul>
</p>

## TextrolSpeech

<p align="justify">
We believe that utilizing natural text descriptions for controlling style in speech is the direction for future development of controllable TTS systems, due to its user-friendliness, generalizability, and interpretability. However, to the best of our knowledge, there is currently no high-quality, large-scale open-source text style prompt speech dataset available for advanced text-controllable TTS models. In this work, we introduce a novel 330-hour clean text style prompt speech emotion dataset called TextrolSpeech. Each style encompasses 5 style factors and 500 distinct natural language text descriptions.
</p>

<p align="center">The figure below shows two example word clouds for style descriptions.</p>
<br>
<img src="figure2.png">
<br>

<p align="center">The figure below shows the distribution of emotions in TextrolSpeech.</p>
<br>
<img src="figure3.png">
<br>

## Diversity

<ruby>Text: A doctor believes this boy to be mad.</ruby>
<table>
	<thead>
		<tr>
			<th style="text-align: center">Style Prompt</th>
            <th style="text-align: center">Audio</th>
		</tr>
	</thead>
	<tbody>
        <tr>
			<td>
            With a low pitch and customary speaking speed, his communication conveys an overall sense of subdued energy.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/98_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            A <b>mad</b> man speaks in a lower tone and a customary pace, evoking an air of diminished enthusiasm.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/68_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The man employs a deep tone and average speaking speed, projecting an overall low vitality.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/132_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The male speaker's energetic discourse is accompanied by a normal pitch and speed.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/56_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
         <tr>
			<td>
            The man's deep voice and dynamic speaking style maintain high energy at a normal speed.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/194_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The man's low-pitched voice maintains an even speaking tempo, evoking a subdued vitality.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/8_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The man employs a low-pitched voice, keeping a regular rhythm and usual energy in conversation.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/136_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The woman's voice is vibrant, high-pitched, and delivered rapidly.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/144_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            A woman's high-pitched voice flows rapidly, reflecting regular energy.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/388_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            His low-pitched speech flows naturally as he maintains a regular cadence and usual energy level.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/308_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The male speaker talks with a deep voice, neither rushed nor sluggish, and maintains balanced energy.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/382_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            With heightened volume, she conveys her high energy.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/396_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            A male speaker's conversation bursts with high energy through his low-pitched voice at a natural speed.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo1/270_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
	</tbody>
</table>

<br>

<ruby>Text: Racism has no place in any sport.</ruby>
<table>
	<thead>
		<tr>
			<th style="text-align: center">Style Prompt</th>
            <th style="text-align: center">Audio</th>
		</tr>
	</thead>
	<tbody>
        <tr>
			<td>
            The male speaker's deep voice and normal speaking tempo combine to create a subdued atmosphere, brimming with a lack of energy.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/159_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            His fast speaking pace and deep voice mirror his lack of energy.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/285_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
		<tr>
			<td>
            With a fast speaking speed, she recounted the adventure.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/13_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            Her voice is sharp, yet her <b>enraged</b> speaking rate is standard.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/163_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            She talks gently, her <b>sorrowful</b> speed unhurried.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/17_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            Speaking with normal energy, she conversed swiftly.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/331_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            A male speaker utilizes a deep tone and normal speaking speed, resulting in a presentation with diminished liveliness.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/213_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The woman's voice resonated slowly, her <b>miserable</b> energy remaining low, pitch high.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/47_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
	<tr>
			<td>
            A deliberate and unhurried male voice, with a low pitch that exudes a tranquil yet grounded energy.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/257_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The woman's voice conveys enthusiasm and a normal tone.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/287_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            His speaking style, marked by a deep pitch and rapid pace, signifies his low energy.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/377_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            In a deliberate manner, she speaks with a deep voice.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/317_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            Speaking slowly and deliberately, her <b>miserable</b> voice exhibited a high pitch and quiet tone.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 300px;"><source src="wav_for_demo/demo2/21_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
	</tbody>
</table>


# Generalization

<ruby>We show the model's ability to generalize to unknown emotions, such as the voice of despair.</ruby>
<table>
	<thead>
		<tr>
			<th style="text-align: center">Style Prompt</th>
            <th style="text-align: center">Text</th>
            <th style="text-align: center">Audio</th>
		</tr>
	</thead>
	<tbody>
        <tr>
			<td>
            The despair woman's high-pitched voice carried a slow speech.
            </td>
            <td>
            A doctor believes this boy to be mad.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 200px;"><source src="wav_for_demo/demo3/1_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The despair woman's high-pitched voice carried a slow yet energetic speech.
            </td>
            <td>
            Racism has no place in any sport.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 200px;"><source src="wav_for_demo/demo3/2_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            Rapidly speaking, the despair man's deep voice resonates with a sense of normal energy.
            </td>
            <td>
            A doctor believes this boy to be mad.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 200px;"><source src="wav_for_demo/demo3/3_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The despair woman's voice resonated slowly, her miserable energy remaining low, pitch high.
            </td>
            <td>
            Racism has no place in any sport.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 200px;"><source src="wav_for_demo/demo3/4_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            A boy said in a desperate voice.
            </td>
            <td>
            One even gave my little dog a biscuit.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 200px;"><source src="wav_for_demo/demo3/5_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>
        <tr>
			<td>
            The despair woman's voice resonated slowly, her miserable energy remaining low, pitch high.
            </td>
            <td>
            One even gave my little dog a biscuit.
            </td>
            <td style="text-align: center">
            <audio controls style="width: 200px;"><source src="wav_for_demo/demo3/6_decompressed.wav" type="audio/wav"></audio>
            </td>
		</tr>        
	</tbody>
</table>

<br>



<style>
.main-content table {
    display: inline-table;
}
table {
    table-layout:fixed;
    width: 100%;
    overflow: hidden;
}
#player{
    width: 100%;
}
</style>
