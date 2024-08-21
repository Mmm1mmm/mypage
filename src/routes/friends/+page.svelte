<script lang="ts">
    import * as Card from "$lib/components/ui/card";
    import * as Avatar from "$lib/components/ui/avatar";
    import Icon from "@iconify/svelte";
</script>
<div class="p-4 pt-9 relative left-[3rem]"><!-- divで囲う --->
    <Card.Root class="w-[50rem] h-[5rem]">
        <Avatar.Root class="w-[50px] h-[50px] relative top-3.5 left-[1rem]"><a href="http://localhost:5174/send"> <!-- relative(相対的に動かす) -->
            <Avatar.Fallback>高専 太郎</Avatar.Fallback>
            <Avatar.Image src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ubSQVjUQ0MATRedUJvku6AHaHa%26pid%3DApi&f=1&ipt=f27a3eb1d4b56626a4f6456235b5e2c2c06718fff76a42f959a200513c624802&ipo=images" alt="@null" />
            </a>
        </Avatar.Root>
        <Card.Header class="-mt-5"> <!-- 違和感のある空白をなくす(上に動かす) -->
            <Card.Title class="relative -top-7 left-[3.75rem]"><p>高専 太郎</p></Card.Title>
            <button class="text-[3rem] relative left-[44rem] -top-[4.25rem] " variant="outlone">
<a href="https://www.youtube.com/watch?v=E4WlUXrJgy4">
  <Icon icon="pixelarticons:gift" />
  </a>
</button>
        </Card.Header>
    </Card.Root>
    <style>
    p{
        font-size: 1.5rem;
    }
    button{
        color: #000;
    }
    </style>
<!------------------------------------------------------------------------------------------->
        <Card.Root class="w-[50rem] h-[5rem] relative top-5">
        <Avatar.Root class="w-[50px] h-[50px] relative top-3.5 left-[1rem]"><a href="http://localhost:5174/send"> <!-- relative(相対的に動かす) -->
            <Avatar.Fallback>高専 花子</Avatar.Fallback>
            <Avatar.Image src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ubSQVjUQ0MATRedUJvku6AHaHa%26pid%3DApi&f=1&ipt=f27a3eb1d4b56626a4f6456235b5e2c2c06718fff76a42f959a200513c624802&ipo=images" alt="@null" />
            </a>
        </Avatar.Root>
        <Card.Header class="-mt-5"> <!-- 違和感のある空白をなくす(上に動かす) -->
            <Card.Title class="relative -top-7 left-[3.75rem]"><p>高専 花子</p></Card.Title>
            <button class="text-[3rem] relative left-[44rem] -top-[4.25rem] " variant="outlone">
<a href="https://www.youtube.com/watch?v=E4WlUXrJgy4">
  <Icon icon="pixelarticons:gift" />
  </a>
</button>

        </Card.Header>
    </Card.Root>
    <!------------------------------------------------------------------------------------------->
        <Card.Root class="w-[50rem] h-[5rem] relative top-10">
        <Avatar.Root class="w-[50px] h-[50px] relative top-3.5 left-[1rem]"><a href="http://localhost:5174/send"> <!-- relative(相対的に動かす) -->
            <Avatar.Fallback>高専 太郎</Avatar.Fallback>
            <Avatar.Image src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ubSQVjUQ0MATRedUJvku6AHaHa%26pid%3DApi&f=1&ipt=f27a3eb1d4b56626a4f6456235b5e2c2c06718fff76a42f959a200513c624802&ipo=images" alt="@null" />
            </a>
        </Avatar.Root>
        <Card.Header class="-mt-5"> <!-- 違和感のある空白をなくす(上に動かす) -->
            <Card.Title class="relative -top-7 left-[3.75rem]"><p>高専 直美</p></Card.Title>
            <button class="text-[3rem] relative left-[44rem] -top-[4.25rem] " variant="outlone">
<a href="https://www.youtube.com/watch?v=E4WlUXrJgy4">
  <Icon icon="pixelarticons:gift" />
  </a>
</button>

        </Card.Header>
    </Card.Root>
    <style>
    p{
        font-size: 2rem;
    }
    button{
        color: #000;
    }
    </style>
    
</div>